# MySQL

# can't use port 9000 in my machine, it has been used by php-fpm when I running docker

## Environment

- Port outside container / inside container local
  - 9000 / 3306

- data volume
  - mysql-volume

## Setting in .env

- VERSION
  - custom the version you want to use in `.env` file, you can find an example in `.env.example`.

## Build

```bash
$ docker-compose up -d
```
