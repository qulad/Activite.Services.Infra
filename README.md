# Activitiy.Services.Infra

.env
```
CONTAINER_NAME=<name_of_container>
MONGO_INITDB_ROOT_USERNAME=<mongo_username>
MONGO_INITDB_ROOT_PASSWORD=<mongo_password>
```

## Tested on Windows 11

## Run with `docker-compose up -d`

Installs:
* MongoDb (persistent NOSQL database)
* MongoDb-Exporter (to see mongodb in prometheus)
* Consul (discovery service)
* Fabio (load balancing)
* Swagger UI (API documentation)
* Seq (centrailized logs)
* Prometheus (monitoring system)
* Grafana (visualize monitoring)

## TODO's
* Add InfluxDb
