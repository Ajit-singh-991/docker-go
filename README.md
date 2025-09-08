<!-- need to create full project readme.md file -->
# Docker Go Example

This is a simple example of a Go application running inside a Docker container.

## Prerequisites

- Docker
- Go

## Build the Docker Image

```bash
docker build -t docker-go .
```

## Run the Docker Container

```bash
docker run -p 8080:8080 docker-go
```

## Access the Application

Open your browser and go to `http://localhost:8080` to see the application in action.
You can also visit `http://localhost:8080/hi` to see the "HI" response.