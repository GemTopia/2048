# 2048

2048 is a number puzzle game. When the squares of the same number are merged together, they will add up. Each round will have an extra square with 2 or 4 written on it, and the game ends when the square cannot be moved. Players have to find a way to make up a square with **2048** (or larger) in this small 16 squares.

# Quick Start

## Run as docker container

open shell and input:

```
TAG="1.1.0-alpha.1"
docker run -d -p 8080:80 ghcr.io/daocloud/dao-2048:$TAG
```

open browser and view http://<server-ip>:8080 .



### Thanks

This image is derived from the Docker Hub image **[alexwhen/docker-2048](https://registry.hub.docker.com/u/alexwhen/docker-2048/)**, thanks to the developer**[alexwhen] (https://github.com/alexwhen)** enthusiastic support.
