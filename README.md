# ViriCiti DevOps Assignment
![](http://turnoff.us/image/en/before-devops-after-devops.png)

## Introduction
This repository holds the ViriCiti DevOps assignment. In this project you will find a folder that has a simple HTTP web-server.

### Web Server
Web Server is a simple stateless service that serves a simple HTTP message. You can deploy as many replicas of this service as you like.

## The assignment
For the assignment we would like you to do the following:

- [ ]  Provision an EKS cluster on AWS with Terraform
  - We will provide you with credentials to log into an AWS sandbox account
- [ ]  Deploy the web-server on the Kubernetes cluster
  - Docker Image: public.ecr.aws/x4g3j7m1/assignment-web-server:latest
  - Make sure the app is reachable from the public internet

### Optional additions
- [ ]  The app has some metrics that can be collected and monitored

