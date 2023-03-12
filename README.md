# devopslab3

## Pull image from Docker Hub

```bash
docker pull flodenoir/devopslab3v1
```

## Run container with a pulled image. Limit of cpus: 1. Limit of memory 512m.

```bash
docker run --memory=512m --cpus=1 --name devopslab3 -p 80:80 flodenoir/devopslab3v1
```

## Stop the container

```bash
docker stop devopslab3
```
