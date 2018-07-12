# stream oriented kurento
#
# VERSION               4.4.3

FROM      ubuntu:14.04
MAINTAINER Patxi Gortázar <patxi.gortazar@gmail.com>

RUN apt-get update \
  && apt-get -y dist-upgrade \
  && apt-get install -y wget

RUN sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 5AFA7A83 \
  && echo "deb [arch=amd64] http://ubuntu.openvidu.io/6.7.1 trusty kms6" | tee /etc/apt/sources.list.d/kurento.list \
  && apt-get update \
  && apt-get -y install kurento-media-server \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

RUN echo "deb  http://dist-aws.telmate.com/repo/ubuntu trusty-prod main" | tee /etc/apt/sources.list.d/tm-trusty-prod.list \
  && wget -O - http://dist-aws.telmate.com/repo/ubuntu/telmate.gpg.key | apt-key add - \
  && apt-get update \
  && apt-get -y install kms-framegrabber \
  && apt-get clean \
  && rm -rf /var/lib/apt/lists/*

EXPOSE 8888

COPY ./entrypoint.sh /entrypoint.sh

ENV GST_DEBUG=Kurento*:5

ENTRYPOINT ["/entrypoint.sh"]