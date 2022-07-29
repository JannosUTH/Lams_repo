SETUP
- `cp .env.dist .env`
- `docker-compose build`
- `docker-compose up mysql`
- `docker-compose up lams`
- RUN LAMS IN http://localhost LOGIN WITH sysadmin/sysadmin.

DB:
- `docker-compose up phpmyadmin`

ADMIN AT http://localhost:8181.
