# Python Flask Docker Lab

A simple Flask application containerized using Docker.

## Technologies

* Python
* Flask
* Docker

## Build

```bash
docker build -t flask-lab:v1 .
```

## Run

```bash
docker run -d \
  --name flask-lab \
  -p 5001:5000 \
  flask-lab:v1
```

## Verify

Open:

http://localhost:5001

Expected response:

Hello from Flask running in Docker!
