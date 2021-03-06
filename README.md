# Udagram 
[![thegux](https://circleci.com/gh/thegux/deployProject.svg?style=svg)](https://app.circleci.com/pipelines/github/thegux/deployProject)

This application was provided by Udacity, as a starter project for the Udacity's Javascript nanodegree course. Udagram is an application whose purpose is to allow users to create posts and share with other people.

## Getting Started

### To view a live demo:
1- Full working application:
http://udagram-bucket-thegux.s3-website-us-east-1.amazonaws.com/

2- API:
http://udagram-api-thegux-dev.us-east-1.elasticbeanstalk.com/api/v0

### To run this project on your own
To get started, first notice that both the frontend and backend are located in this repository. To build this project properly, you must:

1. Make sure you have Node (>= @14.15.1 version), npm (>= @6.14.8), Angular CLI, AWS CLI v2 and Eb CLI installed.
2. Create an environment using AWS Eb and associate the udagram-api with it (Please, remember to initiate elastic beanstalk using eb init)
3. Configure and RDS for running the database and an S3 bucket 
4. Configure a bucket for hosting post pictures
5. Update your deploy.sh with your bucket name
6. Setup environmemt variables listed at the ENV Variables section of this readme in your CI and also in your EBS.
7. Commit your project and wait for the pipeline to finish. Then, access your bucket's URL.

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. `cd starter/udagram-frontend`
2. `npm run test`
3. `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Infrastructure Documentation
[Infrastucture Docs](INFRASTRUCTURE_DOC.md)


## Pipeline Documentation
[Pipeline Docs](PIPELINE_DOC.md)

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

[License](LICENSE.txt)
