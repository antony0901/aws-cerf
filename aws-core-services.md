# Worry 1 #

Understanding of core AWS services, uses, and basic AWS architecture best practices

## List ##

1.Aws compute
  
  a. `EC2`: Elastic Compute Cloud allows you to easily scale virtual machines for your main compute horsepower; note that an opposite approach in AWS is serverless compute with Lambda

2.Aws storage
  
  a. `S3`: Simple Storage Services is object-based, key/value storage for many purposes in AWS
  
  b. `EBS`: Elastic Block Store permits the use of MDD or SDD storage for many purposes, including boot volumes for EC2 instances

3.Aws database
  
  a. `RDS`: Relational Database Service allows you to host many database types in the cloud; this includes Oracle, MS SQL Server, and even Amazon’s own Aurora

  b. `DynamoDB`: a NoSQL database option in the cloud that performs blazing performance and on-demand scalability

  c. `Elastic cache`: creates in-memory caches for impressive performance interaction; this service also supports open standards in caching

4.Aws networking

  a. `VPC`: Virtual Private Cloud provides the networking components needed for an infrastructure including subsets, gateways, routing tables, and security mechanisms

5.Aws management

  a. `CloudWatch`: Permits the monitoring of key services; uses metrics and alarms for a familiar monitoring approach

  b. `CloudTrail`: Permits the tracking of potentially all the API calls to AWS; this allows you detailed analysis of all events no matter the source – Web Console, CLI, SDK, etc.

6.Aws security

  a. `IAM`: Identity and Access Management allows the creation of users, groups, and roles for interacting securely with AWS

7.Aws application integration

  a. `SNS`:the Simple Notification Service allows the generation of email and text notifications based on AWS events

  b. `SQS`: the Simple Queue Service assists you in decoupling components and queuing messages between these components; this service helps the use of micro services for your processing needs

## AWS architecture & best practice ##

The notes below are summarized as follow [AWS architecture](https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf)