## Run stack environment:
```
$ docker-compose -f stack.yml up
```

```
$ docker-compose -f stack.yml stop
```

## MySql client

```
$ mysql -h127.0.0.1 -uroot -proot
```

## Redis client

```
$ docker exec -ti stack_redis_1 redis-cli
```

## RabbitMQ client

```
http://localhost:15672
```

Credentials: guest / guest
