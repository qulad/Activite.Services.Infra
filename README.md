# Activite.Services.Infra

.env
```
CONTAINER_NAME=<name_of_container>
MONGO_INITDB_ROOT_USERNAME=<mongo_username>
MONGO_INITDB_ROOT_PASSWORD=<mongo_password>
INFLUXDB_ADMIN_USER=<influx_username>
INFLUXDB_ADMIN_PASSWORD=<influx_password>
INFLUXDB_DB=<influx_db_name>
```

## Tested on Windows 11

## Run with `docker-compose up -d`

Installs:
* MongoDb (persistent NOSQL database)
* MongoDb-Exporter (to see MongoDb in prometheus)
* Consul (discovery service)
* Fabio (load balancing)
* Swagger UI (API documentation)
* Seq (centrailized logs)
* Prometheus (monitoring system)
* Grafana (visualize monitoring)
* InfluxDb (timeseries DB for Prometheus)
