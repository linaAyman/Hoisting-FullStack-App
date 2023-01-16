# CircleCI Continuous Integration Pipeline

Whenever code gets pushed on the repository main branch, CircleCi performs a new build automatically following a CI pipeline we configured in the config.yml file.

Steps of the pipeline:

1.  Setting up the environment
2.  Install the necessary orbs for deployment (ex: nodejs)
3.  Checks out the code from the main branch of the repository
4.  Install the dependencies for both the backend and front-end
5.  Build both the backend and front-end
6.  Run the unit and integration tests
7.  Deploy the front-end to AWS S3 bucket
9.  Deploys the backend AWS Elastic Beanstalk (EB) environment
