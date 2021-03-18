[![CircleCI](https://circleci.com/gh/jibo-zz/ml-microservice-kubernetes.svg?style=svg)](https://circleci.com/gh/jibo-zz/ml-microservice-kubernetes)

# Udacity - Operationalize a Machine Learning Microservice API

## Project Overview

Deploy a containerized Python flask application to serve out predictions (inference) about housing prices through API calls. It uses a a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access. The data is initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing).

## Getting Started
### Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
