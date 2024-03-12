# Ubuntu Docker Images

This repository contains Dockerfiles for creating Ubuntu Docker images 
with different configurations.

## Simple Image (ubuntu-simple)

This Dockerfile creates a basic Ubuntu image with essential dependencies installed.

### Instructions

1. Build Docker Image:
```
docker build -t ubuntu-simple .
```
2. Run Docker Container:
```
docker run -it ubuntu-simple
```

## Image with Non-Root User (ubuntu-no-root-user)

This Dockerfile creates an Ubuntu image with a non-root user and essential dependencies installed.
Instructions

1. Build Docker Image:
```
docker build -t ubuntu-no-root-user .
```
2. Run Docker Container:
```
docker run -it ubuntu-no-root-user
```