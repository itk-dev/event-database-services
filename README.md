# Event database services

This repository only contains docker setup for share service between
[https://github.com/itk-dev/event-database-api](https://github.com/itk-dev/event-database-api) and
[https://github.com/itk-dev/event-database-imports](https://github.com/itk-dev/event-database-imports).

You need to set the two environments variables `IMPORTS_NETWORK_NAME` and `API_NETWORK_NAME` to connect to the two other
docker compose networks used in production.

For more information about the setup, please see the documentation in
[https://github.com/itk-dev/event-database-imports/tree/develop/docs](https://github.com/itk-dev/event-database-imports/tree/develop/docs)
