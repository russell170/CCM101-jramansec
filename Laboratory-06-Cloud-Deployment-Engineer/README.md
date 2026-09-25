# Laboratory 06 – The Cloud Deployment Engineer

## Mission Overview

This mission focuses on deploying a multi-tier private cloud storage system using Docker Compose. The system uses Nextcloud as the web application and MariaDB as the database. Instead of deploying the containers manually, the infrastructure is defined in a YAML configuration file.

## Objectives

* Explain the concept of multi-tier application architecture.
* Understand the purpose and structure of a `docker-compose.yml` file.
* Use the Linux command-line text editor `nano`.
* Deploy Nextcloud and MariaDB using Docker Compose.
* Document deployment procedures and Infrastructure as Code principles.
* Continue building a professional GitHub Cloud Computing portfolio.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
cat docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

I learned how to create a Docker Compose configuration file and use it to deploy multiple containers as one application stack. I also learned how Nextcloud communicates with the MariaDB database using environment variables and how Docker Compose makes multi-container deployment easier. This activity improved my understanding of multi-tier architecture, YAML configuration, Docker Compose, Infrastructure as Code, and Linux command-line tools.