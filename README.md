sample-docker-mysql
===

## Requirements
- docker 17.06.0+ or later
- docker-compose 1.14.0 or later

## Run

```
$ docker-compose up -d
```

## Down

```
$ docker-compose down
```

## Clean

```
$ docker-compose down
$ rm -rf data/mysql/*
```

## Connection
```
$ mysql -u root -p -P 13306 --protocol tcp
```

## MySQL Configuration
please congiguration to `mysql/conf.d/my.cnf`
