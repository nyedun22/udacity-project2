## Project: Deploy a high-availability web app via CloudFormation

## Project Scenario: 
Create an instagram type of app called Udagram and deploy to AWS. 
Tasked to create the network and server infrastructure. 

## create network stack: 
cd udacity-project2
./create.sh udacityproject-infra network.yml network-parameters.json

## update network stack: 
cd udacity-project2
./update.sh udacityproject-infra network.yml network-parameters.json

## delete network stack: 
cd udacity-project2
./delete.sh udacityproject-infra network.yml network-parameters.json

## create server stack: 
cd udacity-project2
./create.sh udacityproject-server server.yml server-parameters.json

## update server stack:
cd udacity-project2
./update.sh udacityproject-server server.yml server-parameters.json

## delete server stack
cd udacity-project2
./delete.sh udacityproject-server server.yml server-parameters.json

Public link: http://udacit-WebAp-pNb5D3WdQoUN-1193480923.us-east-1.elb.amazonaws.com
