# non detail mode 
```sh
docker-compose up
```

#Open new terminal
```sh
docker ps
```

>> 
CONTAINER ID   IMAGE                   COMMAND                  CREATED          STATUS          PORTS                                       NAMES
e71346908001   node-docker-redis_api   "docker-entrypoint.s…"   38 minutes ago   Up 10 minutes   0.0.0.0:8080->9000/tcp, :::8080->9000/tcp   api
1ca5e121651e   redis:6.2-alpine        "docker-entrypoint.s…"   38 minutes ago   Up 10 minutes   6379/tcp                                    redis
parminder.singh@SG-R913ENEE:/media/parminder.singh/aux_2tb/gfx/dbred/rediscont$ docker exec -it 1ca5e12165

```sh
docker exec -it 1ca5e121651e sh
redis-cli
```