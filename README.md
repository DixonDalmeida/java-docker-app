# java-docker-app

- [Folder Structure](#folder-structure)
- [Local Environment Docker Compose](#local-environment---docker-compose)
    - [docker-compose build](#docker-compose-up)
    - [docker-compose ps](#docker-compose-ps)
    - [docker-compose stop](#docker-compose-stop)
- [Local Environment Monitoring](#local-environment---monitoring)
    - [CAdvisor](#cadvisor)
    - [Portainer](#portainer)
- [Dockerfile](#dockerfile)

## Folder Structure

## Local Environment - Docker Compose

### `docker-compose build`

Build Docker image in docker-compose file using build command

`docker-compose build`

### `docker-compose up`

Up the docker containers 

`docker-compose up`

Up the docker containers in daemon mode

`docker-compose up -d`

### `docker-compose stop`

Stop the docker-compose containers

`docker-compose stop`

## Local Environment - Monitoring

### CAdvisor

Analyzes resource usage and performance characteristics of running containers. 
cAdvisor (Container Advisor) provides container users an understanding of the resource usage and performance characteristics of their running containers. It is a running daemon that collects, aggregates, processes, and exports information about running containers. Specifically, for each container it keeps resource isolation parameters, historical resource usage, and histograms of complete historical resource usage. This data is exported by container and machine-wide.
https://github.com/google/cadvisor

Check out http://localhost:8080 for the CAdvisor Dashboard

### Portainer

Portainer is a lightweight management UI which allows you to easily manage your different Docker environments (Docker hosts or Swarm clusters). Portainer is meant to be as simple to deploy as it is to use. It consists of a single container that can run on any Docker engine (can be deployed as Linux container or a Windows native container, supports other platforms too). Portainer allows you to manage all your Docker resources (containers, images, volumes, networks and more) !

Check out http://localhost:9000 for the Portainer Dashboard

## Dockerfile