## Overview

Creating a small application that communicates with a redis database.

Creating 2 containers: one for our application and one for our redis server

# Method 1

## Building image for our project
```
docker build <your_docker_id>/webdbconnection .
```

## Create redis container
```
docker run redis
```

## Create our project container
```
 docker run iulianlaz/webdbconnection
 ```

# Method 2

```
docker-compose up --build
```
