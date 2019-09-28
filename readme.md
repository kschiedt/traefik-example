# Traefik 2.0 (latest) with Let's Encrypt and whoami as example

This docker compose file provides a basic setup of Traefik with an docker-socket-proxy and whoami as example.

To get this running you have to change a few things:
* Admin mail in static.yml
* Host name in docker-compose.yml
* Make sure to set the correct file permissions on acme.json: `chmod 600 acme.json`
* Create a docker network called "proxy"

Feel free to contribute!
