# docker-valgrind

[![Docker Automated build](https://img.shields.io/docker/cloud/automated/cycycyc/valgrind.svg)](https://hub.docker.com/r/cycycyc/valgrind)

Use docker to run valgrind on x265 and etc.

## Install Docker Desktop

Please first install Docker Desktop from https://www.docker.com/products/docker-desktop.

## Build and valgrind in docker

`docker run --rm -it -v /path/to/code:/mnt -w /mnt cycycyc/valgrind /bin/bash`

Do your work in docker.