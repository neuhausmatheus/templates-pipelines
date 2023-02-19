## GitHub Actions Templates

This repository contains templates for GitHub Actions workflows, aimed at 
making it easier for developers to create and customize their own 
workflows for various tasks.

## Usage

To use a template, simply copy the contents of the template file and paste 
it into your own repository's workflow file, located in 
.github/workflows/. You can then customize the workflow as needed to fit 
your specific needs.

## Available Templates
The following templates are currently available:

argocd_gke_jmeter.yml: A workflow that builds, tests, and deploys a 
project to GKE using ArgoCD and JMeter for continuous deployment testing. 
We also have a automated roll back in case of failure.

matrix_spring.yml: A workflow that build and test a spring boot using 
matrix for multiple versions testing.

service_containers_spring.yml: A workflow that spins up 2 service 
containers to test an spring boot application integration against 
ElasticSearch and CassandraDB.

triggers_matrixes_concurrency_caching_service_containers.yml: A workflow 
that uses all this features to deploy, test and maybe roll back a spring 
boot application.

## Contributing

If you would like to contribute a new template, or improve an existing 
one, please feel free to submit a pull request! We welcome contributions 
from anyone in the community who would like to help make GitHub Actions 
workflows more accessible and customizable.
