# Docker Web Server Project

This project demonstrates how to deploy a simple web server using Docker.

## Features

* Docker containerization
* Nginx web server
* Port mapping
* Simple HTML deployment

## Technologies Used

* Docker
* Nginx
* HTML

## How to Run

```bash
docker build -t my-docker-app .
docker run -d -p 8080:80 my-docker-app
```

Then open: http://localhost:8080
