# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the different containers or services that will be created and managed by Docker Compose. In this project, there are two services: `database`, which uses MariaDB, and `app`, which uses Nextcloud. Docker Compose uses these definitions to deploy the multi-container application.

## How Does Nextcloud Find the Database?

The Nextcloud app container finds the database container through the `MYSQL_HOST` environment variable. In the Compose file, the value is set to `database`:

```yaml
- MYSQL_HOST=database
```

The name `database` matches the database service defined under the `services:` block. This allows the Nextcloud application to communicate with the MariaDB container.

## `docker run` vs. `docker-compose up -d`

The `docker run` command is normally used to create and run an individual container by providing its image, ports, environment variables, and other settings directly in the command. In Mission 4, this method was used to deploy a single container.

The `docker-compose up -d` command is used to deploy multiple related services defined in a `docker-compose.yml` file. In this activity, one command was used to start both the Nextcloud application and MariaDB database in the background. This makes the deployment easier to repeat and manage because the infrastructure configuration is written as code.