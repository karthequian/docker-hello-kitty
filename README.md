# docker-helloworld
A simple helloworld app for docker

A simple nginx helloworld application that helps you learn docker image pulls. Runs on port :80

To pull this image:
```
docker pull karthequian/hello-kitty:latest
```

To run this image:
```
docker run -p 80:80/tcp "karthequian/hello-kitty:latest"
```

Dockerhub link: https://hub.docker.com/r/karthequian/hello-kitty/
