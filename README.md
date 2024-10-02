# geo-ml

## Docker

```
docker build -t envt-5566 .
```

```
docker run -it --rm \
  -p 8888:8888 \
  -v "${PWD}":/home/jovyan/work \
  envt-5566
```