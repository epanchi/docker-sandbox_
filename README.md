# docker-sandbox

Some scripts for testing

# Commands used on

Create and image for proyect

```
    -- To create image first
    docker build -t sandbox/frontend .
```

```
    docker-compose build

    -- run all services
    docker-compose up -d mongo
    docker-compose up -d app

    -- list all services
    docker-compose up -d

    -- list docker containers
    docker ps

    > docker ps
CONTAINER ID   IMAGE      COMMAND                  CREATED              STATUS              PORTS                      NAMES
5fc7d1401995   node-app   "docker-entrypoint.s…"   About a minute ago   Up About a minute   0.0.0.0:4000->4000/tcp     app
5bed9876dc4c   mongo      "docker-entrypoint.s…"   3 minutes ago        Up 2 minutes        0.0.0.0:27017->27017/tcp   mongo

    -- Docker logs
    docker logs mongo

    docker-compose stop

```

# Frontend

Create and image for proyect

```
    -- To create image first
    docker build -t sandbox/frontend .
```
