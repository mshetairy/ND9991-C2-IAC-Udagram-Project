### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

### [Project WebAPP URL](http://udagr-webap-8mb3gasp8cra-843478404.us-east-1.elb.amazonaws.com/)

![img]((0)%20ND%20IAC%20Project%20-%20Diagram.png)

#### project-network.yml
CloudFormation code building the cloud infrastructure.

##### infra-parameters.json
a JSON file for increasing the generic nature of the YAML code. 

#### project-servers.yml
CloudFormation code building the cloud servers.

##### servers-parameters.json
a JSON file for increasing the generic nature of the YAML code. 

In YAML code, the `${EnvironmentName}` would be substituted with `UdagramProject` accordingly.

## Stack Creation on Windows Terminal
```
.\"Supporting Material\create copy.bat" UdagramInfra project-network.yml infra-parameters.json
.\"Supporting Material\create copy.bat" UdagramServers project-servers.yml server-parameters.json
```
