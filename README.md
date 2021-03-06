![devops.png](img/devops.png "")

# DEVOPS quick start examples

This repository contains quic start examples for different technologies like java, nodejs, c# and Azure Function App. Examples are stored in different branches in this repository.
Examples contain simple AngularJS based web application with RESTfull back-end, implementation of back-end depends on used technology, but REST interface remains identical to all examples.

### Branch java-k8s

Java solution uses PostgreSql (Azure database) and Kubernetes Azure Container Service with Jenkins build server.

Whole solutions run in kubernetes cluster (Azure Container Services), CI/CD pipeline also runs in kubernetes cluster and is powered by Jenkins - master node of Jenkins run like separate Pod, all build agents are provisioned on-fly like separate build-agent nodes.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/java-k8s

### Branch java-aks

Java solution uses PostgreSql (Azure database) and Azure Kubernetes Service with Jenkins build server.

Whole solutions run in kubernetes cluster (Azure Kubernetes  Service - AKS), CI/CD pipeline also runs in kubernetes cluster and is powered by Jenkins - master node of Jenkins run like separate Pod, all build agents are provisioned on-fly like separate build-agent nodes.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/java-aks


### Branch cs

C# solution uses Azue SQL Database and Web App with enabled source control deployment.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/cs


### Branch java

Java solution uses PostgreSql (Azure database) and Web App on Linux with deployed Jenkins build server.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/java

### Branch nodejs

NodeJS solution uses MongoDB (Azure Cosmos DB with MongoDB interface) and Web App on Linux with enabled source control deployment.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/nodejs

### Branch funcapp

Function App solution uses Azue Cosmos DB and Function App (JavaScript and C#) with enabled source control deployment.

Solution details and deployment button: https://github.com/valda-z/devops-azure-multiplatform/tree/funcapp



