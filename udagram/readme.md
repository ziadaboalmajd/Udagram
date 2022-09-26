# Udagram

This application is provided to you as an alternative starter project if you do not wish to host your own code done in the previous courses of this nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.

## Getting Started

Clone this repo locally into the location of your choice.
Move the content of the udagram folder at the root of the repository as this will become the main content of the project.
Open a terminal and navigate to the root of the repo
follow the instructions in the installation step
The project can run but is missing some information to connect to the database and storage service. These will be setup during the course of the project

### Dependencies
    - Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

    - npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

    - AWS CLI v2, v1 can work but was not tested for this project

    - A RDS database running Postgres.

    - A S3 bucket for hosting uploaded pictures.

### Installation
Provision the necessary AWS services needed for running the application:

In AWS, provision a publicly available RDS database running Postgres.
In AWS, provision a s3 bucket for hosting the uploaded files.
Export the ENV variables needed or use a package like dotnev/.
From the root of the repo, navigate udagram-api folder cd starter/udagram-api to install the node_modules npm install. After installation is done start the api in dev mode with npm run dev.
Without closing the terminal in step 1, navigate to the udagram-frontend cd starter/udagram-frontend to intall the node_modules npm install. After installation is done start the api in dev mode with npm run start.
### Testing
This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

cd starter/udagram-frontend
npm run test
npm run e2e
There are no Unit test on the back-end

### Unit Tests:
Unit tests are using the Jasmine Framework.

### End to End Tests:
The e2e tests are using Protractor and Jasmine.

### Built With
Angular - Single Page Application Framework
Node - Javascript Runtime
Express - Javascript API Framework
License
License