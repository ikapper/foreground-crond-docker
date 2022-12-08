# Run crond on docker

`Dockerfile2` run crond on user `myuser`; on the other hand, `Dockerfile1` run crond on root user.

Run:

```bash
docker compose up
```

or on old docker-compose:

```bash
docker-compose up
```

If you want to chage user on docker, please replace `Dockerfile1` by `Dockerfile2` in `docker-compose.yml`.