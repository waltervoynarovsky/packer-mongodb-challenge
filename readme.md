Packer and MongoDB Challenge.

Instructions

For the challenge we need to create a Packer file that create us an AMI that is provisioned for MongoDB. We want to see a working machine that has a Mongo shell running inside.
The started code has been provided, with packer file missing. Fill in the packer file and create MongoDB AMI. Launch an instance and connect with it, use command 'mongosh'. 


-Repo on GitHub with Code and README.md

-Complete Packer file to configure MongoDB

-An instance created on AWS (Turned off when not using)

-A screen recording and README explaining what the repo does and showcasing your work


Steps:

-Configure packer.json file to create new AMI

-Go to AWS and launch an instance from the AMI. Remember about your AWS pem key. It's needed for the next step.

-Using public IP of that instance, SSH into it from your machine.

-While inside use command 'mongosh' and then 'show dbs' to check if the DB is working correctly.

![Gif showcasing working instance and DB](https://github.com/waltervoynarovsky/packer-mongodb-challenge/blob/main/Screen%20recording.gif)
