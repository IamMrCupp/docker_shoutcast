
[![IamMrCupp/docker_shoutcast](https://img.shields.io/github/release/IamMrCupp/docker_shoutcast.svg)](https://github.com/IamMrCupp/docker_shoutcast)
[![Build Status](https://travis-ci.org/IamMrCupp/docker_shoutcast.svg?branch=master)](https://travis-ci.org/IamMrCupp/docker_shoutcast) 

# iammrcupp/docker_shoutcast Dockerfile

[![iammrcupp/docker_shoutcast](http://dockeri.co/image/iammrcupp/docker_shoutcast)](https://registry.hub.docker.com/u/iammrcupp/docker_shoutcast/)[![DockerHub release]


This repo is used to create/publish the Shoutcast DNAS Streaming Media Server to the [Docker Hub Registry](https://registry.hub.docker.com/)

The docker container exposes the following:

* Ports
  * 10128 - incoming and outgoing connection
  * 10129 - legacy streaming connections

* Webpages
  * index.html	- main shoutcast page w/ listener and streaming stats
  * admin.cgi	- administration page for shoutcast server


## Base Docker Image
- [ubuntu 14.04](https://registry.hub.docker.com/_/ubuntu/)


## Installation:

1.  Install Docker

2.  Download [automated build](http://registry.hub.docker.com/u/iammrcupp/docker_shoutcast) from the public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull iammrcupp/docker_shoutcast`


##  Usage:

To use the image, type the following:
```
docker run -d -p 10128:10128 -p 10129:10129 iammrcupp/docker_shoutcast
```

