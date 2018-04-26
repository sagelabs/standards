# Developer Operations Standards

topic-namespace: devops

---
## Course: Docker

- Write Dockerfiles
  - Configure a Dockerfile with an image from the Docker Image Repository 
  - Configure a Dockerfile with an image from a private repository
  - Configure a Dockerfile to accept Arguments
  - Add execution steps to a Dockerfile
  - Move files using a Dockerfile command
  - Expose ports within a Dockerfile
  - Use environment variables within a Dockerfile
- Use Docker to automate the build process of an application
  - Use a configured Dockerfile to build an image
  - Run an image in a container
  - Run an image in multiple containers
  - Use Docker commands to execute the installation steps of an application
  - Use Docker with a Continuous Integration tool to automate test runs
  - Use Docker and a Continuous Integration tool to automate the deploy process
- Use Docker to containerize and run a server
  - Use Docker to build and run a server
  - Use Docker to run multiple instances of an image
  - Use environment variables to run a container in different deploy phases
- Use Docker to containerize and run a database server
  - Use a Dockerfile to configure the build process of a database server
  - Use a Dockerfile to configure the migration of schema to the database server from a pre-built image
  - Use a Docker container to host a database with persistent data
  - Use a Dockerfile to add data to a database server from a data source
- Use Docker to containerize and run batch processes
  - Use a Dockerfile to containerize a process that runs periodically
  - Run a batch process in a container on a schedule
  - Run a batch process in a container in response to a trigger


---
## Course: Kubernetes

- Use Kubernetes to define the parameters of an application topology
  - Use Kubernetes pod monitoring commands to check the health and other attributes of a pod
  - Use Kubernetes to label pods and and operate on a group of pods with the same label
  - Use Docker to build and run a container locally using Minikube
- Use Kubernetes to deploy an application to a cloud hosting provider
  - Identify kubernetes control interface elements in the google developer console
  - Use Google Cloud to deploy kubernetes pods to Google Kubernetes Engine cluster

---
## Course: AWS Lambda

- Create an AWS Lambda Function
  - create a script that can be run on AWS Lambda
  - package a script and its dependencies for use on AWS Lambda
  - schedule a function on AWS lambda
- Deploy an AWS Lamba Job using Apex
  - connect Apex to AWS
  - manage environment variables with Apex
  - deploy AWS Lambda functions using Apex
  - view function logs with Apex
