# DevOps Implementation with Flask, GKE, and GCP CI/CD

This repository demonstrates the implementation of the DevOps lifecycle using a basic Flask application. The aim of this project is to showcase the process of building, containerizing, and deploying a Flask application on the Google Kubernetes Engine (GKE) cluster using Google Cloud Platform's (GCP) CI/CD tools.

# Table of Contents
- Introduction
- Application
- DevOps Workflow
- Getting Started
- Prerequisites
- Setup
- CI/CD
- Deployment
- Contributing
- License

# Introduction
DevOps is a set of practices that combine software development (Dev) and IT operations (Ops) aiming to shorten the systems development life cycle and provide continuous delivery with high software quality. This repository demonstrates the implementation of the DevOps principles using a Flask application as an example.

# Application
The application in this repository is a simple "Hello World" Flask app. It's designed to be a basic example, illustrating the core concepts of setting up a Flask application.

# DevOps Workflow
The DevOps lifecycle implemented in this project consists of the following stages:

1. Development: The initial stage involves writing and testing the Flask application code.

2. Containerization: The application is containerized using Docker, allowing for consistent deployment across different environments.

3. Continuous Integration (CI): The CI process is automated using GCP's CI/CD tools. Each code commit triggers automated testing to ensure the application's functionality.

4. Continuous Deployment (CD): Upon successful testing, the application is deployed to the GKE cluster. CD ensures that the deployment process is automated and consistent.



# Getting Started
## Prerequisites

- Docker: Installation 
- Google Cloud SDK: Installation

# Setup
1. Clone this repository:
git clone https://github.com/krsaurav-sudo/GCP_DevOps_Flow.git

2. Navigate to the project directory: cd GCP_DevOps_Flow

3. Build the Docker image: docker build -t flask-app .

4. Run the Docker container locally: docker run -p 5000:5000 flask-app

5. Access the Flask app in your web browser at http://localhost:5000.


# CI/CD
Continuous Integration (CI) and Continuous Deployment (CD) are automated using GCP's CI/CD tools. The CI/CD pipeline includes:

Automated testing of the application code.
Building a Docker image upon successful testing.
Deployment to the GKE cluster.

# Deployment
The deployment of the Flask application is automated using GCP's CI/CD tools. Upon successful testing, the application is automatically deployed to the GKE cluster.

# Contributing
Contributions to this repository are welcome! If you have improvements or bug fixes, feel free to open a pull request. For major changes, please open an issue first to discuss the proposed changes.

# About the Author
This repository has been created by [The Saurav Show](https://twitter.com/sauravstwt). You can find more about me and my other projects on my [GitHub-profile](https://github.com/krsaurav-sudo).

Feel free to explore, learn, and adapt the DevOps principles showcased in this repository for your projects. If you have any questions or suggestions, don't hesitate to open an issue or contact me directly.

Happy DevOps-ing!


