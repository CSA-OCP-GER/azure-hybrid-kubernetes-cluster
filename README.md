# azure-hybrid-kubernetes-cluster

## What we want to achieve

- run kubernetes cluster in azure
- run custom linux container
- run custom windows container
- use private image registry
- CI/CD pipeline with VSTS
- push images to acr
- use images in acr and deploy them to acs / k8s cluster

## Azure Container Registry

- what is it?
- how to create a registry?

## Azure Container Service

- how to create a cluster?
  - portal
  - what can't be done

## ACS Engine

- how it helps to create a cluster
- examples
  - vnet integration
  - hybrid clusters
  - attached disks
- download / install
- define a template
- create service principal
- update config
- create ssh key
- build and deploy

## Example Projects

### ASP.NET Core API

### IIS Container

## Create CI / CD Pipeline

- install token-replace

### Continuous Integration

- build docker images (context!)
- publish to acr

### Continuous Delivery

- add connection to k8s cluster
- deploy images to cluster

## Add Services

- create services to be able to reach the backend pods