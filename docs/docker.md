# Useful docker commands

## docker up

Initially and after code changes:

```bash
docker-compose -f docker-compose-LocalExecutor.yml  up -d
```

## Docker down

To reset the database of the runs to its initial state:

```bash
docker-compose -f docker-compose-LocalExecutor.yml down
```

## Try commands inside the docker container

find the name of the container

```bash
docker ps
```

go in to the container

```bash
docker exec -it <container-id>  bash
```
