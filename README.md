# docker-tutor
https://docs.docker.com/get-started/part2/#apppy

build image:
```
docker build -t friendlyhello .
```

list images
```
docker images
```

run container (add `-d` flag in order to run as daemon):
```
docker run -p 4000:80 friendlyhello
```

list containers:
```
docker ps -a
```

stop container example:
```
docker stop fe23d760bb90
```

remove container example:
```
docker rm fe23d760bb90
```

remove image example:
```
docker rmi c2633687ed88
```
