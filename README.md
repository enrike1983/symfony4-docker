# Symfony 4 Docker env

Symfony 4 + Docker + Docker Compose

## Docker Images
* nginx
* mariaDb

## Setup
Ensure to have docker installed, otherwise download and configure it [HERE](https://docs.docker.com/engine/installation/)

```
$ docker-compose up -d --build
$ vim /etc/hosts  # add 127.0.0.1 www.symfony4.loc
```

## preview
http://www.symfony4.loc

##SSH on aya_app container :

```
$ docker ps
$ docker exec -it [CONTANER_ID|CONTANER_NAME] /bin/bash  #aya_app
$ composer install
```


