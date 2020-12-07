# my docker-airflow

## About 

This repo was forked from https://github.com/puckel/docker-airflow.

It was to be continued indepented from the original repo in order to allow for experimentaion with airflow.

## original documentation 

Here you can find the original documentation from when the repo was forked

[Original documentation for docker-airflow](docs/docker-airflow.md)

## Useful docker commands

See here for how to start and clean the airflow installation

[docker commands](docs/docker.md)

## Udemy course

- [Assignement 1 Dag](docs/assignment1.md)
- [Store Dag](docs/storedag.md)

## Troubleshooting 

### file permission issues

In the end I changed the file permissions of the directory with `chmod 777 <dir>`

### sql connection issues

- [mysql container](docs/mysql.md)
