### Network Security Projects For Phising Data



Network Threat Detection Using Machine Learning is an end-to-end cybersecurity project that detects phishing and malicious network activity using machine learning. It features a complete ML pipeline including data ingestion, validation, transformation, model training, and prediction. The system is built with FastAPI for real-time inference, MongoDB for data storage, and Docker for scalable cloud deployment.

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu


newgrp docker

