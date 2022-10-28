## Containerising your first app
Move to the root of `Chapter-1` before running the commands.

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
