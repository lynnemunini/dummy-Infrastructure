# IG-clone-dummy-Infrastructure
This GitHub repository contains the necessary infrastructure to deploy the dummy application on AWS using CloudFormation.

**Required Infrastructure to deploy the dummy application.**

*Visual aid to understand the CloudFormation script.*
![Infrastructure SVG](dummy.svg)

### Files Overview

[Network CloudFormation](network.yaml)

The network.yml file contains the network configuration, which includes the VPC and the subnets.

[Network Parameters](network-parameters.json)

The network-parameters.json file contains the network parameters.

[Server CloudFormation](server.yaml)

The server.yaml file contains the server configuration.

[Server Parameters](server-parameters.json)

The server-parameters.json file contains the server parameters.

[Update Script](update.sh)

The update.sh file has the command to update the cloudformation stack.

[Create Script](create.sh)

The create.sh file has the command to create the cloudformation stack.

## Usage

1. Update the network-parameters.json and server-parameters.json files with the appropriate values for your deployment.
2. Run ./create.sh to create the CloudFormation stack and deploy the infrastructure.
3. Run ./update.sh to update the CloudFormation stack with any changes made to the parameters or templates.

Note: Make sure you have AWS CLI configured on your local machine and appropriate permissions to access the resources.
