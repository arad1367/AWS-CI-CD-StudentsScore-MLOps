## End to End MAchine Learning Project

1. Docker Build checked
2. Github Workflow
3. Iam User In AWS

## Docker Setup In EC2 commands to be Executed

#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker

## Configure EC2 as self-hosted runner:

## Setup github secrets:

AWS_ACCESS_KEY_ID --> from csv file

AWS_SECRET_ACCESS_KEY --> from csv file

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = Just ECR URL and not repo name

ECR_REPOSITORY_NAME = Your ECR name
