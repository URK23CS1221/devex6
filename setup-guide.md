# Setup Guide

## Installation and Setup Instructions

### Docker
1. **Download Docker**: Go to the [Docker website](https://www.docker.com/get-started) and download the Docker Desktop for your operating system.
2. **Install Docker**: Follow the installation instructions provided for your OS.
3. **Verify Installation**: Open a terminal and run `docker --version` to confirm that Docker is installed correctly.

### kubectl
1. **Install kubectl**: Follow the official guide to Install kubectl from the [Kubernetes website](https://kubernetes.io/docs/tasks/tools/install-kubectl/).
2. **Verify Installation**: Run `kubectl version --client` in your terminal to check if kubectl is installed properly.

### Minikube
1. **Install Minikube**: Follow the instructions on the [Minikube GitHub page](https://minikube.sigs.k8s.io/docs/start/) to install Minikube.
2. **Start Minikube**: After installation, start a Minikube cluster with the command `minikube start`.
3. **Verify Minikube Installation**: Run `minikube status` to check if Minikube is running correctly.