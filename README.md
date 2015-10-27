#Build and Deployment automation using AWS Code Deploy and Jenkins
This is a maven application and is used to automate build and deployment process using below components a. Amazon Code Deploy - as an application environment b. Amazon S3 Services - Storage of revisions/builds b. Jenkins - as a build tool

Whenever push event happens in GIT,jenkins will read this event and start building our application.After successfull build.Jenkins will push build to S3 and start deploying application to code deploy.
