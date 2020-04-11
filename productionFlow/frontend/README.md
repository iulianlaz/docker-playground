This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Run your App inside docker with nginx

```
docker build .
docker run -p 8080:80 <ID_OF_THE_IMAGE>

Open a browser and type: localhost:8080
Thus, you will have your app up and running.
```