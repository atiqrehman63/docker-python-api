# Docker Python API

This project demonstrates how to containerize a simple Python Flask API using Docker.

## Features
- Python Flask API
- Docker containerization
- Port mapping with Docker

## Run the container

Build the image:

docker build -t docker-python-api .

Run the container:

docker run -p 5000:5000 docker-python-api

Open in browser:

http://localhost:5000
