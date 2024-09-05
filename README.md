*Build docker image*
```
docker build -t my-app-old:latest .
```
*Run docker container*
```
docker run --rm -dp 80:80 my-app-old:latest
```