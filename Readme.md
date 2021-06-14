# Ark Fund API using FastAPI Timescaledb Docker

```db
docker run -d --name timescaledb -p 5432:5432 -e POSTGRES_PASSWORD=password timescale/timescaledb:latest-pg12

docker exec -it timescaledb bash

psql -U postgres

create database arkfund;
```
```docker
docker-compose up -d --build
docker-compose exec api bash

docker logs -t containerId
```