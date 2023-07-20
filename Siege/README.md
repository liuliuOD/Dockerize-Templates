# Siege

This is an open source regression test and benchmark utility tool. More description can find [here](https://github.com/JoeDog/siege).

## Environment

- Version
  - siege: 4.0.4

## Build

```bash
$ docker-compose build
```

## Run Container

```bash
$ docker run --rm -it dockliu/siege -c 10 -r 10 -v https://test.liuliu
```

## [Docker Image](https://hub.docker.com/r/dockliu/siege)
