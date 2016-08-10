# Docker Image: Alpine + Updates + Daily build
## Goal of the project : 
The prupose of this project is to provide a Docker Image for Linux Alpine that is : 
- directly derived from the official [Alpine Docker Image](https://hub.docker.com/_/alpine/),
- when a new container is created, it runs the updates with the commands ```apk update``` and ```apk upgrade```

Please read the Dockerfile for more informations.
