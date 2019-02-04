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
$ docker exec -ti redis redis-cli
```

## RabbitMQ client

```
http://localhost:15672
```

## Elasticsearch + kibana

```
http://localhost:5601
```
Credentials: guest / guest
