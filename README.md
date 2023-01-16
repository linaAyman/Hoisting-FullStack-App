# Hosting a Full-Stack Application

[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://app.circleci.com/pipelines/github/linaAyman/Hoisting-FullStack-App)


### **udagram is a full stack web application hosted on AWS, it's the final project under Udacity's Full Stack Nanodegree Program.**



---

## Hosted links

- Front-end link (UI)
  http://udagram-bucket-bylina.s3-website.us-east-2.amazonaws.com/

- Back-end link (API) http://udagram-api-dev.eba-5c3ehym7.us-east-1.elasticbeanstalk.com/api/v0/

---
# Infrastructure Overview

The Udagram full stack application is hosted on the Amazon Web Services Cloud with the following services:

1.  AWS RDS - relational database service instance running PostgreSQL
2.  AWS Elastic Beanstalk (EB) - scalable service hosting the API backend
3.  AWS Simple Storage Service (S3) - scalable storage hosting the UI front-end

---

# Amazon Web Services

### AWS Simple Storage Service (S3)

- s3 image

  ![alt text](screenshots/4-S3%20bucket%20and%20files.PNG 'AWS S3')

### AWS Elastic Beanstalk (EB)


- Ok status

  ![alt text](screenshots/1-eb.PNG 'AWS EB Health and recent activity')

- Elastic Beanstalk configuration

  ![alt text](screenshots/5-EB%20configs.PNG 'Elastic Beanstalk configuration')

### AWS Relational Database Service (RDS)

![alt text](screenshots/3-RDS.PNG 'AWS RDS Postgres')

---

## CircleCI

`This full stack web application is deployed with a CircleCI continuous integration pipeline.`

**Pipeline features**:

1. Install and build both the backend and front-end applications
2. Deploy both the backend and front-end applications


- Secrets/env variables in the application are configured inside CircleCi and sent to the production on Elastic Beanstalk.



- screenshot of the CricleCi env variables
![alt text](screenshots/6-circleCi%20env%20variables.PNG 'CircleCi environment variables')
---

## Documentation

Documentation and diagrams about the pipeline steps and infastructure is in the [documentation](https://github.com/linaAyman/Hoisting-FullStack-App/tree/main/documentation) folder.

---
