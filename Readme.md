# Cloud DevOps Engineer Capstone Project

## About the Project: 

>Created a CI/CD pipeline for a  website that deploys to a cluster in AWS EKS using Blue/Green Deployment.

## Project Requirement (Installations):

> To be able to use this CI/CD pipeline you will need to install:

* Jenkins
* Blue Ocean Plugin in Jenkins
* Pipeline-AWS Plugin in Jenkins
* Docker
* Pip
* Eksctl
* AWS Cli
* Kubectl

## The files included are:
```sh
* /Images - Screenshot the result of deploy.
* /Create-clusters - CloudFormation Script of Cluster Pipeline file 
* /Deploy-containers - Deployment Script of Containers Pipeline file
* Jenkinsfile - Jenkinsfile for Creating Pipeline
* Dockerfile - Dockerfile that builds the image 
* green-controller.json - Creates a replication controller green pod
* green-service.json - Creates the green service
* blue-controller.json - Creates a replication controller blue pod
* blue-service.json - Creates the blue service
* index.html - Web site Index file.
```

## Running the project:
```sh
*  Follow the steps in screenshots of Images folder.
```
