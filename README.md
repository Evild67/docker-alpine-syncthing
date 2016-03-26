[![Docker Stars](https://img.shields.io/docker/stars/evild/alpine-syncthing.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-syncthing/)
[![Docker Pulls](https://img.shields.io/docker/pulls/evild/alpine-syncthing.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-syncthing/)
[![ImageLayers Size](https://img.shields.io/imagelayers/image-size/evild/alpine-syncthing/latest.svg?style=flat-square)](https://hub.docker.com/r/evild/alpine-syncthing/)

# Alpine Syncthing

This image is based on [evild/alpine-base](https://hub.docker.com/r/evild/alpine-base/)

## Version
- `0.12.21`, `latest` [(Dockerfile)](https://github.com/Evild67/docker-alpine-syncthing/blob/master/Dockerfile)


## How to use this image

```
docker run -p 8080:8080 -p 22000:22000 -p 21025:21025/udp --name syncthing alpine-syncthing
```
