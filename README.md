# ReBAC project with OpenFGA

## Table of contents
* [General info](#general-info)
* [Setup](#setup)

## General info
This is a sample relationship-based access control (ReBAC) project based on OpenFGA.

## Setup
To start the OpenFGA service in docker use included docker-compose file.

```
docker-compose up -d
```

REST/OpenFGA.http file contains a bunch of http requests to:
* Create a store
* Configure an authoriztion model (from JSON file converted from DSL)
* Add relationship tuple
* Check access
