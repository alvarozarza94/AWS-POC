# aws-microservices-event-drivern-architecture
This repo contains an application composed of a web application supported by two serverless microservices (AWS Lambda). At runtime, the microservices will communicate across accounts using an event-driven architecture with Amazon SNS and DynamoDB. 


## Deploying the serverless microservices sample application

#### 1. Pre-requisites

You will need one AWS account.

#### 2. Clone the sample Lambda function GitHub repository

[Clone](https://help.github.com/articles/cloning-a-repository/) the [microservices sample application](https://github.com/aws-samples/aws-cross-account-serverless-microservices.git) GitHub repository.

From your terminal application, execute the following command:

```commandline
git clone https://github.com/alvarozarza94/aws-microservices-event-drivern-architecture.git
```

This creates a directory named `aws-microservices-event-drivern-architecture` under your current directory, which contains the code for the Serverless Microservices sample application.
