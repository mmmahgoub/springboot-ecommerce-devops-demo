# Spring Boot Ecommerce DevOps Demo

A production_style e_commerce backend built with Java, Spring Boot, PostgreSQL, Docker, Kubernetes, and GitHub Actions.

## Features
- REST API (Products)
- PostgreSQL database
- Docker & Docker Compose
- Kubernetes manifests
- CI/CD with GitHub Actions
- Swagger API docs

## Run Locally
docker run -e DB_HOST=db -e DB_USER=user -e DB_PASS=password \
  --network springboot-ecommerce-devops-demo_default \
  springboot-ecommerce-devops-demo-app

  Access the app
URL: http://localhost:8080
API example: http://localhost:8080/api/products