# iammrcupp/docker_shoutcast Dockerfile

This repo is used to create/publish our 128k Shoutcast Master to the Docker Hub Registry

## Base Docker Image
- [ubuntu](https://registry.hub.docker.com/_/ubuntu/)


## Installation:

1.  Install Docker

2.  Download [automated build](http://registry.hub.docker.com/u/iammrcupp/shoutcast_128k) from the public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull iammrcupp/shoutcast_128k`


##  Usage:

To use the image, type the following:
```
docker run -d -p 10128:10128 -p 10129:10129 iammrcupp/shoutcast
```

