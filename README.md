# udagram-cloudformation-iac

## Project Description

The main objective of this project is to deploy a high-availability web application on the aws infrastructure. To achieve this objective, we use cloudformation to write scripts that configure and deploy the needed infrastructure as well as dependecies/packages needed to run the web application.

## Project structure

The scripts in this codebase can be categorised into two categories:

* network layer: script to setup the networking layer of the application. This can be found in the file named `udagram_infrastructure.yml`. In addition, parameters used in the setup the network layer can be found in `udagram_infrastructure-parameters.json`

* application layer: scripts to setup the necessay ec2 instances, install application dependencies, autoscaling groups, loadbalancers and security groups. The file that contains the above script is named `udagram_servers.yml` and while the file that contains the parameters used is named `udagram-servers-params.json`.


## Access the web application

The web application can be accessed using this url: http://udagr-WebAp-JUI0KFIM4MEJ-308737016.us-east-1.elb.amazonaws.com


