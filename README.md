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
![Screenshot 2023-02-20 112733](https://user-images.githubusercontent.com/71128303/220039113-16fa0c80-1e61-4cc9-8938-d682d2f34ddd.jpg)


--- Deploy a sample web app to AWS Elastic Beanstalk
![Screenshot 2023-02-20 112851](https://user-images.githubusercontent.com/71128303/220039172-68096f53-0d65-4704-91c1-6a462fc05acc.jpg)

![Screenshot 2023-02-20 112909](https://user-images.githubusercontent.com/71128303/220039230-1d46b62b-1624-4f9f-b18e-53f556d98922.jpg)


--- Test the sample web app 
![Screenshot 2023-02-20 113622](https://user-images.githubusercontent.com/71128303/220039396-7ee5136b-44bc-42fc-abfe-80937d77016f.jpg)


## STEP 3: CREATE BUILD PROJECT

--- Configure the AWS CODEBUILD project
![Screenshot 2023-02-20 113712](https://user-images.githubusercontent.com/71128303/220039443-5a421a39-1a7a-44f9-bbd8-c2e762136b97.jpg)

![Screenshot 2023-02-20 114054](https://user-images.githubusercontent.com/71128303/220039534-70285cf8-deed-43c1-97c6-15e457063d93.jpg)

![Screenshot 2023-02-20 114107](https://user-images.githubusercontent.com/71128303/220039581-04ec0a90-6ed6-4739-a128-4162d62d0c42.jpg)

![Screenshot 2023-02-20 114119](https://user-images.githubusercontent.com/71128303/220039613-2acce547-a706-405a-8ca0-54484baa950e.jpg)


--- Create a Build Spec file for the project
![Screenshot 2023-02-20 114131](https://user-images.githubusercontent.com/71128303/220039676-b678541e-203f-46f7-b70e-64d08e75905c.jpg)


--- Test the code build project
![Screenshot 2023-02-20 114306](https://user-images.githubusercontent.com/71128303/220039739-26505823-7487-4df3-b96a-c65171899c91.jpg)


## STEP 4: CREATE DELIVERY PIPELINE

--- Create a new pipeline
![Screenshot 2023-02-20 114439](https://user-images.githubusercontent.com/71128303/220039774-41c8ccc9-a3f4-4aa8-8af6-d833f7abe0f8.jpg)

![Screenshot 2023-02-20 114515](https://user-images.githubusercontent.com/71128303/220039808-357329b6-1184-437b-ab67-bee5f0ccb880.jpg)


--- Configure the source stage
![Screenshot 2023-02-20 114618](https://user-images.githubusercontent.com/71128303/220039869-8c358dda-ffe3-41c1-9ac2-717b6cc47981.jpg)


--- Configure the build stage
![Screenshot 2023-02-20 114659](https://user-images.githubusercontent.com/71128303/220039901-03c7771e-c4a7-4858-9905-8b226b74d1d4.jpg)


--- Configure the deploy stage
![Screenshot 2023-02-20 114742](https://user-images.githubusercontent.com/71128303/220039935-e3321214-26d8-4125-bf3f-b1f6e539c635.jpg)


--- Watch first pipeline execution
![Screenshot 2023-02-20 115305](https://user-images.githubusercontent.com/71128303/220040100-958f4bff-a15d-491d-9731-6252fc8298d7.jpg)

![Screenshot 2023-02-20 115242](https://user-images.githubusercontent.com/71128303/220040058-e64cd8a4-1e5c-4998-b982-09e2663d1f8c.jpg)



### STEP 5: FINALIZE PIPELINE AND TEST

--- Create review stage in pipeline
![Screenshot 2023-02-20 115424](https://user-images.githubusercontent.com/71128303/220040128-a3201244-f840-4a4f-920f-750fd053b8a6.jpg)
![Screenshot 2023-02-20 115539](https://user-images.githubusercontent.com/71128303/220040165-6a5c76a3-7998-4901-821f-bfee90c39e10.jpg)


--- Push a new commit to your repo

--- Monitor the pipeline and manually approve the changes
![Screenshot 2023-02-20 115956](https://user-images.githubusercontent.com/71128303/220040231-552f2d32-388a-4145-8764-7a6b02969cbd.jpg)
![Screenshot 2023-02-20 120120](https://user-images.githubusercontent.com/71128303/220040255-270eee23-196d-4ecf-9c43-99361a758c24.jpg)


