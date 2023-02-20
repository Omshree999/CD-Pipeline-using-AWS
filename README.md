# CD Pipeline using AWS

This repository contains a sample Node.js web application built using [Express](https://expressjs.com/), meant to be used for deploying this project.

## What I accomplished in this project

--- Set up a GitHub repository for the application code
--- Create an AWS Elastic Beanstalk environment to deploy the application
--- Configure AWS CodeBuild to build the source code from GitHub
--- Use AWS CodePipeline to set up the continuous delivery pipeline with source, build, and deploy stages

## APPLICATION ARCHITECTURE

![image](https://user-images.githubusercontent.com/71128303/220037446-d84fb7d6-605e-4c45-bfa1-b374513cff61.png)

## STEP 1: SETUP GITHUB REPO

--- Fork a GitHub repository to create a new one
--- Push a change in your new repo
--- Test your changes

## STEP 2: DEPLOY WEB APP

--- Configure and create an AWS Elastic Beanstalk environment

--- Deploy a sample web app to AWS Elastic Beanstalk

--- Test the sample web app 

## STEP 3: CREATE BUILD PROJECT

--- Configure the AWS CODEBUILD project

--- Create a Build Spec file for the project

--- Test the code build project

## STEP 4: CREATE DELIVERY PIPELINE

--- Create a new pipeline
--- Configure the source stage
--- Configure the build stage
--- Configure the deploy stage
--- Watch first pipeline execution

### STEP 5: FINALIZE PIPELINE AND TEST

--- Create review stage in pipeline
--- Push a new commit to your repo
--- Monitor the pipeline and manually approve the changes,
