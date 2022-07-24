# Custom docker-dind image with bash and docker compose

## Build image

- Clone this repository
- Run:

```bash
docker build . -t kinoba/docker-dind
```

## Publish docker image

```bash
docker push kinoba/docker-dind
```