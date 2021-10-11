# Deploy Infrastructure as Code (IAC)

## Task
Using CloudFormation to deploy architectural patters to deploy any cloud application.
Also included an infrastructure diagram for my application.

## Case Scenario
<p>Your company is creating an Instagram clone called Udagram. Developers pushed the latest version of their code in a zip file located in a public S3 Bucket.You have been tasked with deploying the application, along with the necessary supporting software into its matching infrastructure.
This needs to be done in an automated fashion so that the infrastructure can be discarded as soon as the testing team finishes their tests and gathers their results.

<p/>

## Requirements 
- Creating Launch Configuration for the application Server
- 2 vPCUs with atleast 4gb RAM,instance size and machine type.
- 10GB disk space to avoid running into issues.  

**BONUS** :Bonus points if you add http:// in front of the load balancer DNS Name

## Creating the CloudFormation Stack on AWS.
 ### Using script to deploy server stack
 ```
 ./create.sh serverdemo  server.yml server.json
 
```
 ### Using script to deploy infrastructure stack 
 ```
 ./create.sh infrademo  infra.yml infra-parameters.json
 ```
