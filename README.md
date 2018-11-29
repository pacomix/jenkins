# DO NOT USE STILL. IT IS A WIP.

# Base Jenkins master for building pacomix's repos
This repository contains the necessary Docker fine tuned image using Jenkins 2.153-alpine as base. Specific plugin lists and configurations are inside this image so any repository under the pacomix user can be built without problems.

# Usage
Just build the docker image and launch it as usual with
```
docker run --publish 8080:8080 --publish 5000:5000 pacomix/jenkins:2.153-alpine
```
