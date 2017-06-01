# github.com/mattes/migrate docker image

Docker image for database migration tool github.com/mattes/migrate built on Golang's official Alpine image.

## Migrate

Version: 3.0.1

* https://github.com/mattes/migrate

## Building

```
docker build -t='migrate' .
```

## Running

```
docker run --rm andrewjones/migrate:latest -database postgres://localhost:5432/database up 2
```
