# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A two-tier architecture is a system divided into two main parts: the Web/Application Tier and the Database Tier. In this laboratory, the Web/Application Tier is represented by the Nextcloud application, while the Database Tier is represented by the MariaDB database.

## Web/Application Tier

The Web/Application Tier is responsible for serving the user interface and handling requests from users. In this activity, the Nextcloud container provides the web application that users access through a web browser. It communicates with the database to store and retrieve information needed by the application.

## Database Tier

The Database Tier is responsible for storing persistent data used by the application. In this activity, MariaDB stores information such as user accounts and file metadata. The database runs in its own container and communicates with the Nextcloud application container.

## Why Separate Them?

Separating the web application and database into two containers makes the system more organized and easier to manage. Each container has a specific responsibility, so the application and database can be managed or updated separately instead of placing everything in one container. This also follows the multi-tier architecture used in the laboratory, where Nextcloud and MariaDB work together as separate services.