# Hosting a Full-Stack Application



### **udagram is a full stack web application hosted on Amazon Web Services and is the final project under Udacity's Full Stack JavaScript Developer Nanodegree Program.**



---

## Hosted links

- Front-end link (UI)
  http://aml-udagram-frontend.s3-website-us-east-1.amazonaws.com

- Back-end link (API) http://udagram-api-app-dev.us-east-1.elasticbeanstalk.com

---

# Amazon Web Services

### AWS Simple Storage Service (S3)

- s3 image

  ![alt text](screenshots/5.buckets-files.png 'AWS S3')

### AWS Elastic Beanstalk (EB)

- check

  ![alt text](screenshots/1-eb-check.png 'AWS EB')

- Ok

  ![alt text](screenshots/2.recent-event.png 'AWS EB')

- Elastic Beanstalk configuration

  ![alt text](screenshots/10.enviroment-variables.png 'Elastic Beanstalk configuration')

### AWS Relational Database Service (RDS)

![alt text](screenshots/6.RDS.png 'AWS RDS')

---

## CircleCI

`This full stack web application is deployed with a CircleCI continuous integration pipeline.`

**Pipeline Highlights**:

1. Able to run install and build for both backend and front-end applications
2. Able to deploy for both backend and front-end applications


- All the secrets found in the application are configured inside CircleCi and passed to the production application.



- screenshot of the CricleCi secrets

---

## Documentation

Documentation about the architecture, infrastructure description, app dependencies, and the pipeline process are found inside the [docs] folder.

---
