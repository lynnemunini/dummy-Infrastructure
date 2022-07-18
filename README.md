# IG-clone-dummy-Infrastructure

**Required Infrastructure to deploy the dummy application.**

*Visual aid to understand the CloudFormation script.*
![Infrastructure SVG](dummy.svg)

*Files Overview*

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