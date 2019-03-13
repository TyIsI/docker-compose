# docker-compose

Dockerized docker-compose

## Info

The `docker-compose` script mounts `/etc`, `/var/run/docker.sock` and the current directory to run.

It also pulls COMPOSE_PROJECT_NAME from the local environment and defaults to the current host working directory.

## Install

```
wget -O /usr/local/bin/docker-compose https://raw.githubusercontent.com/TyIsI/docker-compose/master/docker-compose
chmod a+x /usr/local/bin/docker-compose
```

## Use

Run as regular.

```
docker-compose <args>
```
