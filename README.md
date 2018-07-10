[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation badge](https://readthedocs.org/projects/fiware-orion/badge/?version=latest)](http://doc-kurento.readthedocs.org/en/latest/)
[![Docker badge](https://img.shields.io/docker/pulls/fiware/orion.svg)](https://hub.docker.com/r/fiware/stream-oriented-kurento/)
[![Support badge]( https://img.shields.io/badge/support-sof-yellowgreen.svg)](http://stackoverflow.com/questions/tagged/kurento)

[![][KurentoImage]][Kurento]

Copyright © 2013-2016 [Kurento]. Licensed under [Apache 2.0 License].

kurento-docker
==============

Kurento utilities for [Docker] containers.

What can you find here
----------------------

Here you can find the Dockerfile for generating Docker Images. Following is an inventory of which image you can build in every folder:

* aws-cli

Docker image with AWS Cli.

* coturn

Docker image with Coturn. 

* coturn-auth

Docker image with Coturn using authentication.

* dev-chef

Docker image with Chef client.

* dev-documentation

Docker image for Kurento documentation.

Build: https://ci.openvidu.io/jenkins/job/Development/job/adm_container_kurento_dev_documentation_merged/

Used for:
  Build Kurento documentation and push it to Read the doc.

* dev-integration

Build: https://ci.openvidu.io/jenkins/job/Development/job/adm_container_kurento_dev_integration_merged/

Used for:

Integration test

* dev-integration-browser

* dev-media-server

Docker image to build Kurento Media Server.

Build: https://ci.openvidu.io/jenkins/job/Development/job/adm_container_kurento_dev_media_server_merged

* docker

Install Kurento Media server in a container. This was created to test if our APT Repositories work properly. It's now deprecated.

* kurento-media-server

Official Docker Image for Kurento Media Server.

Build: 
https://ci.openvidu.io/jenkins/job/Development/job/Kurento_media_server_docker_trusty/
https://ci.openvidu.io/jenkins/job/Development/job/Kurento_media_server_docker_xenial/

* kurento-media-server-dev

Nightly versions of Kurento media server.

Build:
https://ci.openvidu.io/jenkins/job/Development/view/5%20-%20Build/view/Docker/job/Kurento_media_server_docker_trusty_nightly/
https://ci.openvidu.io/jenkins/job/Development/view/5%20-%20Build/view/Docker/job/Kurento_media_server_docker_xenial_nightly/

* kurento-test-files

Docker image to download test files from SVN repository. Deprecated.

* release-media-server

Docker image for relase Kurento Media Server.

Build: https://ci.openvidu.io/jenkins/job/Development/job/container_release_media_server

* svn-client

Docker image with svn client.


What is Kurento
---------------

Kurento is an open source software project providing a platform suitable 
for creating modular applications with advanced real-time communication
capabilities. For knowing more about Kurento, please visit the Kurento
project website: http://www.kurento.org.

Kurento is part of [FIWARE]. For further information on the relationship of 
FIWARE and Kurento check the [Kurento FIWARE Catalog Entry]

Kurento is part of the [NUBOMEDIA] research initiative.

Documentation
-------------

The Kurento project provides detailed [documentation] including tutorials,
installation and development guides. A simplified version of the documentation
can be found on [readthedocs.org]. The [Open API specification] a.k.a. Kurento
Protocol is also available on [apiary.io].

Source
------

Code for other Kurento projects can be found in the [GitHub Kurento Group].

News and Website
----------------

Check the [Kurento blog]
Follow us on Twitter @[kurentoms].

Issue tracker
-------------

Issues and bug reports should be posted to the [GitHub Kurento bugtracker]

Licensing and distribution
--------------------------

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Contribution policy
-------------------

You can contribute to the Kurento community through bug-reports, bug-fixes, new
code or new documentation. For contributing to the Kurento community, drop a
post to the [Kurento Public Mailing List] providing full information about your
contribution and its value. In your contributions, you must comply with the
following guidelines

* You must specify the specific contents of your contribution either through a
  detailed bug description, through a pull-request or through a patch.
* You must specify the licensing restrictions of the code you contribute.
* For newly created code to be incorporated in the Kurento code-base, you must
  accept Kurento to own the code copyright, so that its open source nature is
  guaranteed.
* You must justify appropriately the need and value of your contribution. The
  Kurento project has no obligations in relation to accepting contributions
  from third parties.
* The Kurento project leaders have the right of asking for further
  explanations, tests or validations of any code contributed to the community
  before it being incorporated into the Kurento code-base. You must be ready to
  addressing all these kind of concerns before having your code approved.

Support
-------

The Kurento project provides community support through the  [Kurento Public
Mailing List] and through [StackOverflow] using the tags *kurento* and
*fiware-kurento*.

Before asking for support, please read first the [Kurento Netiquette Guidelines]

[documentation]: http://www.kurento.org/documentation
[FIWARE]: http://www.fiware.org
[GitHub Kurento bugtracker]: https://github.com/Kurento/bugtracker/issues
[GitHub Kurento Group]: https://github.com/kurento
[kurentoms]: http://twitter.com/kurentoms
[Kurento]: http://kurento.org
[Kurento Blog]: http://www.kurento.org/blog
[Kurento FIWARE Catalog Entry]: http://catalogue.fiware.org/enablers/stream-oriented-kurento
[Kurento Netiquette Guidelines]: http://www.kurento.org/blog/kurento-netiquette-guidelines
[Kurento Public Mailing list]: https://groups.google.com/forum/#!forum/kurento
[KurentoImage]: https://secure.gravatar.com/avatar/21a2a12c56b2a91c8918d5779f1778bf?s=120
[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0
[NUBOMEDIA]: http://www.nubomedia.eu
[StackOverflow]: http://stackoverflow.com/search?q=kurento
[Docker]: https://www.docker.com/
[Read-the-docs]: http://read-the-docs.readthedocs.org/
[readthedocs.org]: http://kurento.readthedocs.org/
[Open API specification]: http://kurento.github.io/doc-kurento/
[apiary.io]: http://docs.streamoriented.apiary.io/
