
# Flask Docker CI/CD

A simple Flask web app containerized with Docker and automated with GitHub Actions.

## Stack
- Python / Flask
- Docker
- GitHub Actions

## Run locally
docker build -t flask-app .
docker run -p 5000:5000 flask-app

## CI Pipeline
Every push to main automatically builds the Docker image and tests the app.
