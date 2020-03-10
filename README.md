# Simple Docker config for nginx, Varnish and PHP

This is a simple Docker setup to play around PHP and Varnish.

To power up the Docker:

```bash
docker-compose up
```

If you do any changes on Docker file, don't forget to build up the changes:

```bash
docker-compose up --build
```

Entering Docker containers:
* PHP - `docker exec -it marek_php /bin/bash`
* nginx - `docker exec -it marek_nginx /bin/bash`
* Varnish - `docker exec -it marek_varnish /bin/bash`