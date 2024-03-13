# MySQL and MongoDB project

## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd Group-08`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `MYSQL_ROOT_PASSWORD` the default value is **mysql_paswd_2023**
* `MYSQL_DATABASE` the default value is **company_database**
* `MYSQL_USER` the default value is **angelo**
* `MYSQL_PASSWORD` the default value is **@_angelotheman**
* `MONGO_INITDB_ROOT_USERNAME` the default value is **root**
* `MONGO_INITDB_ROOT_PASSWORD` the default value is **angelotheman**
* `ME_CONFIG_MONGO_ADMINUSERNAME` the default value is **root**
* `ME_CONFIG_MONGO_ADMINPASSWORD` the default value is **angelotheman**

## Access to mysql: 
* `localhost:3306`
* **Username:** angelo 
* **Password:** @_angelotheman 

## Access to PhpMyAdmin: 
* **URL:** [http://localhost:8080](http://localhost:8080)
* **Username:** myadmin@myadmin.org
* **Password:** angelotheman

## Access to mongodb:
* `localhost:27017`
* **Username:** root
* **Password:** angelotheman

## Contributors
* Angel Oduro-Temeng Twumasi <angel@trestleacademyghana.org>
* Benjamin Kwame Ampah <abenjamin@trestleacademyghana.org>
