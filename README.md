## Simple flask app

*Build docker image*
```
docker build -t simple-flask-app:latest .
```
*Run docker container*
```
docker run --rm -dp 80:80 simple-flask-app:latest
```