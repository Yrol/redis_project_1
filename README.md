## A Playground project for Redis

This project serves as a playground for experimenting with Redis features.

### Starting Redis in Docker
Go to `docker` folder and execute command below
```
docker-compose up
```

### Accessing the Redis container and the Redis CLI

Access Redis container
```
docker exec -it redis bash
```

Access Redis CLI (once inside the Redis container)
```
redis-cli
```
