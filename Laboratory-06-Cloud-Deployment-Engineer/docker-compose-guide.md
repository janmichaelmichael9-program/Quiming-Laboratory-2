# Docker Compose Guide

## What Does the Services Block Do?

The `services:` block defines the containers that make up the application. In this project, it defines the MariaDB database and the Nextcloud application.

## How Does Nextcloud Find the Database?

Nextcloud uses the `MYSQL_HOST=database` environment variable. The name `database` matches the database service name in the Docker Compose file, allowing the application to find the database through Docker's network.

## Difference Between docker run and docker-compose up -d

The `docker run` command is used to start an individual container with specified settings. The `docker-compose up -d` command starts the services defined in the Compose file in the background. Docker Compose makes it easier to manage multiple connected containers using one configuration file.
