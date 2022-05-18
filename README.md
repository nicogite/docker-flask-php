# Docker-compose : Request Flask API with PHP

- Build a flask server from a custom dockerfile
- Build a php server from an existing image
- Make them communicate !

## Prerequisites

Docker version >= 20.10.16
docker-compose version >= 1.25.0

## Commands

Build the local environment :

*docker-compose up*

Access the webserver :

*http://localhost:8080/*

Erase container :

*docker system prune -f*

Erase images :

*docker rmi {image_name}*

Erase all images :

*docker rmi $(docker image list)*