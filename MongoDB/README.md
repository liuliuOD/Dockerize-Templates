# MongoDB

## Environment

- Port outside container / inside container local
  - 9500 / 27017

- data volume
  - mongodb-volume

- version
  - MongoDB: 7.0

## Build

```bash
# MongoDB v7.0
$ docker-compose -f docker-compose-7_0.yml build
```

## Run Container

```bash
$ docker-compose -f docker-compose-7_0.yml up -d
```
