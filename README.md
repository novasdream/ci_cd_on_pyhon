# Overview

With this project we will use has an scaffolding with python web service.
we will learn how to use an complete CI CD. 

It can be useful to work in another projects.


## Project Plan
https://trello.com/b/GI6auPFF/udacity-devops-course


## Instructions

Flow of Deployment 


![Diagram of deployment](image/azure-devops-framework.png?raw=true "Diagram of deployment")

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell
![All tests passed](image/azure-cloud-shell.png?raw=true "Test Passed")

* Passing tests that are displayed after running the `make all` command from the `Makefile`

![All tests passed](image/passing-tests-min?raw=true "Test Passed")

* Output of a test run

![All tests passed](image/test-passed.png?raw=true "Test Passed")

* Successful deploy of the project in Azure Pipelines.
![Successful deploy](image/successful-deploy-azure-pipeline.png?raw=true "Successful deploy")

* Running Azure App Service from Azure Pipelines automatic deployment

![Completed with Success azure pipelines](image/azure-pipeline.png?raw=true "Completed with Success azure pipelines")

* Successful prediction from deployed flask app in Azure Cloud Shell.
The output should look similar to this:

![Output sample from an successful deployed prediction app](image/test-app-deployed-min.gif?raw=true "Output sample from an successful deployed prediction app")

* Output of streamed log files from deployed application
```
2020-10-15T17:16:04.252803672Z [2020-10-15 17:16:04,252] INFO in app: JSON payload: %s json_payload
2020-10-15T17:16:04.262692871Z [2020-10-15 17:16:04,262] INFO in app: inference payload DataFrame: %s inference_payload
2020-10-15T17:16:04.263385471Z [2020-10-15 17:16:04,262] INFO in app: Scaling Payload: %s payload
2020-10-15T17:16:04.291993268Z 172.16.0.1 - - [15/Oct/2020:17:16:04 +0000] "POST /predict HTTP/1.1" 200 35 "-" "curl/7.64.1"
2020-10-15T17:16:04.300275067Z 172.16.0.1 - - [15/Oct/2020:17:16:04 +0000] "GET / HTTP/1.1" 200 32 "-" "ReadyForRequest/1.0 (AppInit)"
```
> 

## Enhancements

It can be improved to be deployed in stage environment, before production

## Demo 

<TODO: Add link Screencast on YouTube>


