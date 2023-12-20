# Ngrok

## Setting in .env

> You can find an example about following parameters in `.env.example`.

- NGROK_AUTHTOKEN
  - set to the auth token that apply from ngrok. 
- CONTAINER_NAME
  - set to the container name you want to expose.
- PORT
  - set to the port of service running inside your container.
- NETWORK
  - set to the network that the container you want to expose.

## Build

```bash
$ docker compose up -d --build
```

## References

- [ngrok](https://ngrok.com/docs/using-ngrok-with/docker)
