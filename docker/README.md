# Build dockerfile

## Build the dockerfile image

```bash
docker build -t mi_imagen:v1 .
```

## Check docker local images

```bash
docker images
```

## Save image

```bash
docker save mi_imagen > mi_imagen.tar.gz
```

## Delete image

```bash
docker rmi mi_imagen:v1
```

## Load local image

```bash
docker load -i mi_imagen.tar.gz
```
