## Overview
Simple node web server running on a docker container

## Build docker
```
docker build -t <your_docker_id>/simpleweb .
```
## Run docker (create and start container)
```
 docker run <your_docker_id>/simpleweb
```
## Run docker (create and start container); also, create port mapping in order to allow access to web server from container
```
docker run -p 5000:8080 <your_docker_id>/simpleweb
```

Now, open your web browser and access your web server on
```
localhost:5000
```
