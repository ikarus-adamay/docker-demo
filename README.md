## Containerising your first app

- building container image
```bash
docker build -t workshop:v1 -f dockerfile.v1 .
```

- listing all the images on your machine
``` bash
docker images
```

- running images 
```bash
docker run -p 3000:3000 workshop:v1 .
```

- listing all the containers running on your machine 
```bash
docker ps
docker ps -a
```

- stopping a running container 
```bash 
docker stop <container_ir or container_name>
```

- digging through the image
```bash
docker 
```

- commom commands

``` bash
$ docker pull ubuntu:18.04 (18.04 is tag/version (explained below))
$ docker images (Lists Docker Images)
$ docker run image (creates a container out of an image)
$ docker rmi image (deletes a Docker Image if no container is using it)
$ docker rmi $(docker images -q) (deletes all Docker images)
```