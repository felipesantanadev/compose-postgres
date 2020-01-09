# Docker Compose for Postgresql and PgAdmin


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Run `docker-compose up -d` from the repository folder


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **123456**
* `PGADMIN_PORT` the default value is **5252**
* `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin4@pgadmin.org**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **123456**

## Access to postgres: 
* `localhost:5435`
* **Username:** postgres (as a default)
* **Password:** 123456 (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:5252`
* **Username:** pgadmin4@pgadmin.org (as a default)
* **Password:** 123456 (as a default)

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `POSTGRES_USER`, by default: `postgres`
* **Password** as `POSTGRES_PASSWORD`, by default `123456`