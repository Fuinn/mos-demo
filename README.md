# mos-demo-docker

All-in-one MOS application launched using docker containers.

## Prerequisites

* Install Docker
* Download the [docker-compose.yml](docker-compose.yml) file

## Launching the App

Execute the following command from the location of the `docker-compose.yml` file:
```
sudo docker-compose up
```

The following MOS components are then available:
* Web user interface: ``localhost:4200``
* Browsable API: ``localhost:8000/api``
* Admin page: ``localhost:8000/admin``

The default MOS admin user credentials are:
* username: ``mos``
* password: ``demo``

## Resetting all Data

Execute the following command from the location of the `docker-compose.yml` file:
```
sudo docker-compose down --volumes
```
