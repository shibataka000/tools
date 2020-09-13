#!/bin/bash
##################################################
# Delete all docker containers and docker images.
##################################################
DOCKER_PS=`docker ps -aq`
if [ "$DOCKER_PS" != "" ];  then
    docker ps -aq | xargs docker rm
fi
DOCKER_IMAGES=`docker images -aq`
if [ "$DOCKER_IMAGES" != "" ]; then
    docker images -aq | xargs docker rmi
fi
