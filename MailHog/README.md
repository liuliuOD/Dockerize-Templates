# Mailhog

## Environment

- Port outside container / inside container local
  - 1025 / 1025
  - 8025 / 8025
- data volume
  - mailhog-volume
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

- [GitHub](https://github.com/mailhog/MailHog)
- [Docker](https://hub.docker.com/r/mailhog/mailhog)
