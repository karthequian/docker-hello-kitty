# docker-hellokitty
A simple hellokitty app for docker

A simple nginx hellokitty application that helps you learn docker image pulls. Runs on port :80 inside the container. This application will run nginx and return a hello kitty image

To pull this image:
```
docker pull karthequian/hellokitty:latest
```

To run this image:
```
docker run -p 80:80/tcp "karthequian/hellokitty:latest"
```

Dockerhub link: https://hub.docker.com/r/karthequian/hellokitty/
