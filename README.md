# mos-demo

MOS demo launched via docker-compose.

## Prerequisites

* Install Docker
* Download the [docker-compose.yml](docker-compose.yml) file

## Pulling the latest Images

Execute the following command from the location of the `docker-compose.yml` file:
```
sudo docker-compose pull
```

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

## Stopping the App

The `Ctrl+C` keyboard command will stop the app, or alternatively execute the following command from the location of the `docker-compose.yml` file:
```
sudo docker-compose stop
```

## Resetting all Data

Execute the following command from the location of the `docker-compose.yml` file:
```
sudo docker-compose down --volumes
```
