# Photopea
This image is based on https://github.com/DUOLabs333/Photopea-Offline.

The image uses Alpine Linux.

## Running the image

```
docker run --rm --name photopea -p 80:8887 -t kovaszab/photopea
```

## Building the image
```
docker build . -t kovaszab/photopea
```