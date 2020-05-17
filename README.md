# AWS CodeStar Serverless web application with CheckPoint CloudGuard Security
============================================================================
a simple Node.js web service deployed by AWS CloudFormation to AWS Lambda and Amazon API Gateway and secured with CloudGuard Workload SAST and DAST security. 
CloudGuard Workload SAST is Proact with Source code scanning and Posture management 
CloudGuard Workload DAST is FSP for runtime security of the serverless function and can be applied selectively per function.

## What's Here
----------------


* README.md - this file
* buildspec.yml - this file is used by AWS CodeBuild to package your
  application for deployment to AWS Lambda
* index.js - this file contains the sample Node.js code for the web service
* template.yml - this file contains the AWS Serverless Application Model (AWS SAM) used
  by AWS CloudFormation to deploy your application to AWS Lambda and Amazon API
  Gateway.
* tests/ - this directory contains unit tests for your application
* template-configuration.json - this file contains the project ARN with placeholders used for tagging resources with the project ID

AWS CodeStar allows to create a project to deploy a serverless application using the AWS CodePipeline chosing an IDE and a runtime like node.js
