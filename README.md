# Machine Learning Microservice Application

[![SKLearn](https://circleci.com/gh/neorusse/sklearn-k8s.svg?style=svg)](https://circleci.com/gh/neorusse/sklearn-k8s) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

### Project Task

The project goal is to operationalize a pre-built SKLearn Machine Learning Microservice Application using Kubernetes, which is an open-source system for automating the management of containerized applications by doing the following:

- Test project code using linting
- Create a Dockerfile to containerize this application
- Deploy the containerized application using Docker and make a prediction
- Improve the log statements in the source code for the application
- Configure Kubernetes and create a Kubernetes cluster
- Deploy the containerize app to Kubernetes cluster and make a prediction
- Use CircleCI as a CICD tool

### Technology Used

Flask

pytest

PyLint

Docker

Kubernetes

CircleCI

### Building from Source

You need Python 3 and a bash-like shell.

## Setup the Environment

- Create a virtualenv and activate it
- Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone: `python app.py`
2. Run in Docker: `./run_docker.sh`
3. Run in Kubernetes: `./run_kubernetes.sh`

### Kubernetes Steps

- Setup and Configure Docker locally
- Setup and Configure Kubernetes locally
- Create Flask app in Container
- Run via kubectl

### Verify the application is running

> Application listens on port 8000

---

### Testing

This project uses [pytest](https://docs.pytest.org/en/latest/)

### License

[MIT](https://opensource.org/licenses/MIT)

### Author

[Russell Nyorere](https://neorusse.github.io/)
