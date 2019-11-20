# Postgresql & Adminer powered by compose


## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd compose-postgres`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **changeme**
* `ADMINER_DESIGN` the default value is **nette**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** changeme (as a default)

## Access to Adminer:
* **URL:** `http://localhost:5050`
* **System:** `PostgreSQL`
* **Username:** postgres (as a default)
* **Password:** changeme (as a default)
* **Database:** postgres (as a default)
