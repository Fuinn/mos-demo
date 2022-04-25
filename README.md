# mos-demo-docker

All-in-one MOS application launched using docker containers.

## Prerequisites

* Docker

## Launching the App

Execute the following script:
```
./scripts/mos-demo-run.sh
```

The following MOS components are then available:
* Web user interface: ``localhost:4200``
* Browsable API: ``localhost:8000/api``
* Admin page: ``localhost:8000/admin``

The default MOS admin user credentials are:
* username: ``mos``
* password: ``demo``

## Resetting all Data

Execute the following script:
```
./scripts/mos-demo-reset.sh
```
