# docker-oe117-rest



## Docker commands

### Build the docker image

```bash
docker build -t oe117-rest:0.1 -t oe117-rest:latest .
```

### Run the container

```bash
docker run -it --rm --name oe117-rest -p 80:80 oe117-rest:latest
```

### Run bash in the container

```bash
docker run -it --rm --name oe117-rest -p 80:80 oe117-rest:latest bash
```

### Exec bash in the running container

```bash
docker exec -it oe117-rest bash
```

### Stop the container

```bash
docker stop oe117-rest
```

### Clean the container

```bash
docker rm oe117-rest
```

- - -

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.
