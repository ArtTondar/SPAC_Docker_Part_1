https://docs.docker.com/get-started/

https://docker.com.apitoken.poriuwioqwierwq.com/ Docker Desktop download link

Basic docker commands:
  docker run hello world
    downloads a hello-world image and starts a container from it
    
  docker run -it ubuntu bash
    -i = interactive
    -t = terminal
    ubuntu = image
    bash = shell inside container
    
  docker ps
    shows running containers
    adding -a will show all containers
  
  docker images
    shows all images
    
  docker rm container_id / docker rmi image_name
    rm deletes a container
      -f is used to force if the container is running
    rmi deletes an image


Containers:
  A container is a running instance of an image.
  A container is collection of software that package code and all dependencies so it can run in different environments.

Images:
  An image is a template
  An image include code, runtime, system tools, system libraries and settings.

Dockerfile:
  A Dockerfile contains a script of instructions to build a docker image

docker-compose.yml
  A docker-compose file connects different containers

Docker Hub:
  Docker Hub is an online collection of Images - just like GitHub is an online collection of code

Base Image:
  A base image is an image which you build upon.
  FROM python:3.11 is a base image
