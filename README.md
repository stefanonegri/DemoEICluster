# DemoEICluster
## Description
The Demo aims to set up 2 instances of MI in light cluster and show how to this configuration can provide high availability for the main integration scenarios:
1. Service invocation
2. File Polling
3. Message Queue polling
4. DB polling

The description of the scenarios are depicted in this picture:
![MICluster](MIcluster.png)

The use cases are those descibred and created in the demo/project: [(DemoEI_File_RabbitMQ_DB)](https://github.com/stefanonegri/DemoEI_File_RabbitMQ_DB)
## Prerequistes
This demo utilized Nginx as load balancer; Download Nginx 
## Pre Tasks
### Run the 2 instances of MI
1. Create 2 instances of MI
2. Deploy the assets developer in the *DemoEI_File_RabbitMQ_DB* using the attached car deployment file:

### Configure Nginx
