# Dockerized WordPress Setup

## Getting Started

### Requirements
* [Docker](https://docs.docker.com/get-docker/) must be installed
* [Docker Compose](https://docs.docker.com/compose/) must be installed

### Set-up
1. Creates *.env* from *.env.template* and configure it if you need it. `cp .env.template .env`.
2. Execute `docker-compose up -d` in your project's root directory to run. The *./wordpress* folder was created and inside are all WordPress files.
3. Open [localhost:8080](http://localhost:8000/) (Or the port configured with `WORDPRESS_PORT_80` in your *.env*) in your web browser to finish the WordPress installation.

## Common issues
* Be sure that the port configured in `WORDPRESS_PORT_80` is empty in your machine
* The `.gitignore` file is configured to track only WordPress plugins and themes

## To-do
* Add WP-Cli
* Add phpMyAdmin
