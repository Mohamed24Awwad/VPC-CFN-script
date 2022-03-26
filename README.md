
# VPC Deploy Servers

Deploy Servers with AWS Cloudformation Script( Creating VPC, Public/Private Subnets, IGW "InternetGateway Service",NatGateway, Route Tables)


# AWS WebApp Archeticure

![App Archeticture](https://github.com/Mohamed24Awwad/VPC-CFN-script/blob/8ce1bfe06bae3f1b18e8052bb89cdc222b535d3e/AWSWebApp.jpeg?raw=true)



## Tech Stack

**Language:** Bash ,YAML , JSON , AWS CloudFormation

**Tools:** AWS CLI



##  Dependancies


##### 1. AWS account
You would require to have an AWS account to be able to build cloud infrastructure.

##### 2. VS code editor
An editor would be helpful to visualize the image as well as code. Download the VS Code editor [here](https://code.visualstudio.com/download).

##### 3. An account on www.lucidchart.com
A free user-account on [www.lucidchart.com](www.lucidchart.com) is required to be able to draw the web app architecture diagrams for AWS.

##### 4. Having AWS CLI Extension on your VSCode


## Installation

Feel Free to clone the app.

```bash
  https://github.com/Mohamed24Awwad/VPC-CFN-script.git

```
    

## Instructions

### How to run the supporting material?
######  You can run this script in two easy steps:
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Create the network infrastructure
# Check the region in the create.sh file
./create.sh myFirstStack infrastructure.yml params.json
# Create servers
# Change the AMI ID and key-pair name in the servers.yml
# Check the region in the update.sh file
./update.sh mySecStack servers.yml server-parameters.json



## Author

- [@MohamedAwwad](https://github.com/Mohamed24Awwad)

