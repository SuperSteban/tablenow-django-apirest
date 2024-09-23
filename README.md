# 🚀 
## API REST Application for Managing Restaurant Reservations 📃🪑🍣🌮

This project is an API developed with Django and Django Rest Framework to manage restaurant reservations. It uses PostgreSQL as the database and Nginx as a reverse proxy, with all components containerized using Docker.

***The primary goal is to gain hands-on experience in building a RESTful API using Django and Django Rest framework while learning and mastering Docker for containerized deployment.***


#### Requirements to run this app
  - Docker 🐋
  - Docker-compose 🐳
##### Installation dev
```sh

docker compose -f docker-compose.dev.yaml up --build
```
``detach mode``
```sh

docker compose -f docker-compose.dev.yaml up -d --build
```

##### Installation using nginx reverse 
```sh

docker compose -f docker-compose.prod.yaml up --build
```

[^note]:
The guide a was following to dockerize a django app is [Dockerizing Django with Postgres, Gunicorn, and Nginx](https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/#gunicorn) from Michael Herman
