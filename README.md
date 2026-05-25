# Flask CI/CD Demo

A simple Flask application demonstrating CI/CD pipeline implementation using GitHub Actions.

## Features
- Python Flask web app
- Virtual environment setup
- GitHub Actions CI pipeline
- Automated dependency installation
- Automated validation/testing

## Tech Stack
- Python 3.12
- Flask
- GitHub Actions



## Build Docker Image

```bash
docker build -t flask-ci-app .
```

## Run Docker Container

```bash
docker run -p 5001:5000 flask-ci-app
```
