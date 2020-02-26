# github.com/golang-migrate/migrate docker image

Docker image for database migration tool github.com/golang-migrate/migrate built on Golang's official Alpine image.

## Migrate

Version: 4.9.1

* https://github.com/golang-migrate/migrate

## Building

```
docker build -t='andrewjones/migrate' .
```

## Running

```
docker run --rm andrewjones/migrate:latest -database postgres://localhost:5432/database up 2
```
