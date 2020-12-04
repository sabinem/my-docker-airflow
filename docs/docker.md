# Useful docker commands

## docker up

Initially and after code changes:

```
docker-compose -f docker-compose-LocalExecutor.yml  up -d
```

## Docker down

To reset the database of the runs to its initial state:

``` 
docker-compose -f docker-compose-LocalExecutor.yml down
```
