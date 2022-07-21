# circleci-excercisesolution1
## Prerequisites
1. Key pair - You should have an AWS EC2 key pair already created in your AWS Console, and downloaded to your local mahcine. We are assuming the key pair name is udacity.pem.
2. A public Github repository.
3. An account in the CircleCI.

## Instructions
#### Step 1. Set up a CircleCI project
* Go to https://app.circleci.com/ and set up a new project associated with your Github repository
* If you repo does not contain a ./circleci/config.yml file, it will prompt you to create one. Choose a "hello-world" starter config file. The CircleCI      will attempt the first build process. Don't worry if it fails at this moment.


#### Step 2. Set up Environment variables
* To use the AWS CLI in your jobs you'll need to the following environment variables to the in Circle CI > Project Settings > environment variables. The value of these variables can be fetched from the AWS IAM user.

* If not already, create an AWS IAM user with programmatic access, and it will generate these credentials.
,,,
AWS_ACCESS_KEY_ID
AWS_DEFAULT_REGION
AWS_SECRET_ACCESS_KEY
,,,

