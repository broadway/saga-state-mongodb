broadway/saga-state-mongodb
===========================

Saga state persistence for [broadway/broadway-saga](https://github.com/broadway/broadway-saga) using MongoDB.

> Note: this component is highly experimental.

![build status](https://github.com/broadway/saga-state-mongodb/actions/workflows/ci.yml/badge.svg)

# Installation

```
$ composer require broadway/saga-state-mongodb
```

Testing
-------
For testing you need a running MongoDB instance.
To start a local MongoDB you can use the provided [docker-compose.yml](https://docs.docker.com/compose/compose-file/):

```
docker-compose up -d
```

To run the tests:

```
./vendor/bin/phpunit
```
