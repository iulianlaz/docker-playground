
## Build docker
```
docker build -t iulianlaz/simpleweb .
```
## Run docker (create and start container)
```
 docker run iulianlaz/simpleweb
```
## Run docker (create and start container); also, create port mapping in order to allow access to web server from container
```
docker run -p 5000:8080 iulianlaz/simpleweb
```