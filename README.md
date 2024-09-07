# Awesome Selfhosted
A curated list of free services and web applications which can be hosted on Docker. This list only includes apps that I'm actually using or have used in the past.

This repo is also hosting an  App Template definition that can be used with Portainer. Spin up Portainer and reference the following file to use the templates:

https://raw.githubusercontent.com/Horizon0156/awesome-selfhosted/main/templates.json

```
docker run -d -p 9443:9443 --name portainer --restart=always -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer-ce
```

## Databases
* [qdrant](https://qdrant.tech/): Vector Search Engine for the next generation of AI applications.
* [MongoDB](https://www.mongodb.com): Open-source document-oriented database.
* [PostgreSQL](https://www.postgresql.org): The most advanced open-source database.
* [Redis](https://redis.io): Open-source in-memory data structure store.

## Finances 
* [Actual](https://actualbudget.org): Fast and privacy-focused app for managing your finances.

## Messaging
* [RabbitMQ](https://www.rabbitmq.com): Highly reliable enterprise messaging system.

## Operating Systems
* [Alpine](https://www.alpinelinux.org): Alpine Linux is a security-oriented, lightweight Linux distribution based on musl libc and busybox.

## Password Manager
* [Bitwarden](https://bitwarden.com): An open source password manager for securely storing, managing, and sharing sensitive online data such as passwords, passkeys, and credit cards.

## Smart Home
* [Homebridge](https://homebridge.io/): Homebridge allows you to integrate with smart home devices that do not natively support HomeKit.
* [Node-RED](https://nodered.org): A flow based programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.
* [RaspberryMatic / CCU](https://raspberrymatic.de): RaspberryMatic is a free, lightweight operating system alternative for an OpenSource-based "homematicIP CCU" under your control.

## Storage
* [File Browser](https://filebrowser.org/): A web based file managing interface within a specified directory and it can be used to upload, delete, preview, rename and edit your files.
* [Minio](https://min.io/): A distributed object storage server built for cloud applications and devops.
* [Registry](https://hub.docker.com/_/registry): Distribution implementation for storing and distributing of container images and artifacts

## Webhosting
* [Caddy](https://caddyserver.com): Open-source web server / reverse proxy with automatic HTTPS written in Go
* [Caddy Docker Proxy](https://github.com/lucaslorentz/caddy-docker-proxy?tab=readme-ov-file#server): This plugin enables Caddy to be used as a reverse proxy for Docker containers via labels.
* [Ghost](https://ghost.org): Free and open-source blogging platform:
* [nginx](https://nginx.org): High performance web server.