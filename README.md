# Creating a Development Environment with Docker Compose, Redis, and MongoDB

Setting up a robust development environment is a crucial step for any developer, and Docker has become an invaluable tool for achieving this. Docker allows you to create isolated and reproducible environments, making it easier to manage dependencies and streamline development workflows. In this blog post, we will guide you through creating a development environment using Docker and integrating Redis and MongoDB, two popular databases often used in web development.

## What You'll Need

Before we dive into the details, make sure you have the following prerequisites:

1. Docker installed on your system. You can download and install Docker from the official website (<https://www.docker.com/get-started>).

2. A code editor or Integrated Development Environment (IDE) of your choice.

3. Basic knowledge of Docker commands and containers.

## Steps to get started

```bash
git clone https://github.com/techsimpledotin/docker-rest-express-redis-mongo-container.git

cd docker-rest-express-redis-mongo-container

docker compose up 
```

### Check `apis.http` file for api endpoints

```
### test route
http://localhost:4000

### Get All users
http://localhost:4000/users

### Create User
POST http://localhost:4000/users
content-type: application/json

{
  "firstName": "John",
  "lastName": "Doe",
  "email": "john.doe@example.com",
  "password": "mysecretpassword"
}

### Delete ALl users
DELETE http://localhost:4000/users

```
