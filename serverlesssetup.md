First we need to create  an account on serverless website which is partnered with AWS

then we need to launch an Ec2 instance on AWS console just to clone the code .
 
 we have to install Nodejs as serverless is written in Nodejs so first we need to install node JS in our EC2 server.
 
 For that you can follow this link
 https://computingforgeeks.com/install-node-js-14-on-ubuntu-debian-linux/
 
 first update bu sudo apt update command on your server
 and install Nodejs 
 curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
 
 sudo apt -y install nodejs
 
 and check version using this command node -v  and npm -v for npm version
 
 ![image](https://github.com/padmalakum/serverless-project/assets/92623347/8ddb8907-db72-4a8f-9dd4-bd28a387a814)
then we need to install serverless framework 
 sudo npm install -g serverless
 and we need to install aws cli to access aws from the console.
 sudo apt install awscli
 and then create a folder project and cd into that and run this command
 serverless --org=padma09
 so that we can start our serverless project by choosing a new one or existing
 
 Here we are going to do a simple Nodejs HTTp API  project
 
![image](https://github.com/padmalakum/serverless-project/assets/92623347/21378a37-b7dc-4706-8f41-46faa65c1b62)

then it will download Nodejs http api template and we have to give aws access keys by creating a user in aws console thru IAM and create access and secret access keys and enter those values here
then it starts deploying our app
![image](https://github.com/padmalakum/serverless-project/assets/92623347/913b9102-4a3a-49b6-9632-e44d2a84c575)


 
