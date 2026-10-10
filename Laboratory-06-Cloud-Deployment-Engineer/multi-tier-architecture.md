# Two-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture is an application structure that uses two separate parts: the web/application tier and the database tier. These two parts communicate with each other to provide the services needed by users.

## The Web/Application Tier

The web/application tier handles the user interface and HTTP requests. In this laboratory, Nextcloud is the web application that allows users to access and manage their files through a browser.

## The Database Tier

The database tier stores persistent information, such as user accounts and application data. In this laboratory, MariaDB serves as the database for Nextcloud.

## Why Separate Them?

Separating the web application and database into two containers makes the system easier to manage and maintain. It also allows each service to be configured and updated separately. Docker Compose helps connect and manage both containers as one application.
