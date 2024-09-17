# Deployment Of Containerized Java Application with CI/CD Groovy-Scripts
Demo on deployment of containerized Java Application with CI/CD using Groovy Scripts

## Case Studies
I used an example Java program. This is containerized and deployed in the K8s environment using Docker.

Continues Integration – Continuous Deployment

Loaded Shared Libraries into existing pipeline from GitHub
Build job is configured in Jenkins
Source code is checked-out from GitHub
Unit tests are using jUnit
Code Analysis using Check style
Code is packaged (.war) using maven and the artifact is stored in AWS S3 Bucket
Using Docker, an image is created with .war file and its dependencies, docker image is then pushed to Docker Hub.
Deployment into K8s Containerization environment using Jenkins pipeline
Create a Release Tag and push it Github.
