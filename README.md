# Introduction 
Repo to try Canary k8s deployment on AzureDevOPS pipelines services

## Folders and repo structure
1. ./_devops        - Azure DevOps pipelines folder
2. ./app            - simpleapp code in python + Docker file to buid image
3. ./manifests      - k8s deployments manifests to deploy sampleapp in k8s
4. ./misc           - k8s deployments manifests to deploy load tests and monitor apps
5. ./presentation   - PowerPoint presentation of this project

## Prerqusites
Docker Engine - you will need it to build Docker container of sample app

## CI/CD 
CI/CD (and continous deployment) coded in Azure DevOPS pipelines (check ./_devops/azure-pipelines.yml)

## Build and Test
Once your PR is approved and merged Azure Pipeline will build the infra

## Contribute to infra
Clone repo, make PR, have fun.