# github.com/mattes/migrate docker image

Docker image for database migration tool github.com/mattes/migrate build on Golang's offical Alpine image.

## Migrate

Version: 3.0.1

* https://github.com/mattes/migrate

## Running

### docker

```
docker run --rm andrewjones/migrate:latest -database postgres://localhost:5432/database up 2
```

