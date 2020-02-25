his project operationalizes a Python flask app—in a provided file, app.pythat serves out predictions about housing prices through API calls sklearn model that has been trained to predict housing prices in Boston.

This project operationalizes the working, machine learning microservice using Kubernetes and Docker which is an open-source system for automating the management of containerized applications. The following things were done in this project.

Project code was tested using linting
Docker was used to containerize this application
Deployed the containerized application and made a prediction
Improved the log statements in the source code for this application
Configured Kubernetes and create a Kubernetes cluster using minikube
Deployed a container using Kubernetes and make a prediction
Upload a complete Github repo with CircleCI to indicate that your code has been tested
Setup the Environment
Create a virtualenv and activate it
Run make install to install the necessary dependencies
Running app.py
Standalone: python app.py
Run in Docker: ./run_docker.sh
Run in Kubernetes: ./run_kubernetes.sh
Kubernetes Steps
Setup and Configure Docker locally
Setup and Configure Kubernetes locally
Create Flask app in Container
Run via kubectl
