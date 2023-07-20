# Qdrant

## Environment

- Port outside container / inside container local
  - 6333 / 6333 # Restful
  - 6334 / 6334 # gRPC

- data volume
  - qdrant-volume

- version
  - 1.0.1

## Build

```bash
$ docker-compose build
```

## Run Container

```bash
$ docker-compose up -d
```

## Reference

- [GitHub](https://github.com/qdrant/qdrant)
- [Docker](https://hub.docker.com/r/qdrant/qdrant)
