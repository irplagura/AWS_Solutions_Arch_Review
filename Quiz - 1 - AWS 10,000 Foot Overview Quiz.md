## 1. Which of the below are factors that have helped make public cloud so powerful? (Choose 2) 
- [X] The ability to try out new ideas and experiment without upfront commitment 
- [ ] Traditional methods that are used for on-premise infrastructure work just as well in cloud 
- [ ] No special skills required 
- [X] Not having to deal with the collateral damage of failed experiments 

Public cloud allows organisations to try out new ideas, new approaches and experiment with little upfront commitment. 
If it doesn't work out, organisations have the ability to terminate the resources and stop paying for them Further information: 
https://docs.aws.amazon.com/aws-technical-content/latest/aws-overview/six-advantages-of-cloud-computing.html

## 2. Which of the below are compute service from AWS? (Choose 2) 
- [x] EC2 
- [ ] S3
- [x] Lambda 
- [ ] VPC

Both Lambda and EC2 offer computing in the cloud. 
S3 is a storage offering while VPC is a network service. Further information: 
https://aws.amazon.com/ec2/https://aws.amazon.com/lambda/https://aws.amazon.com/s3/https://aws.amazon.com/vpc/

## 3. Which of the below are database services from AWS? (Choose 2)
- [ ] EC2 
- [x] RDS
- [ ] S3 
- [x] DynamoD8

RDS is a service for relational databases provided by AWS. 
DynamoDB is AWS' fast, flexible, no-sql database service. S3 provides the ability to store files in the cloud and is not suitable for databases, while EC2 is part of the compute family of services. 
Further information: 
https://aws.amazon.com/dynamodb/
https://aws.amazon.com/rds/https://aws.amazon.com/ec2/
https://aws.amazon.com/s3/

## 4. In which of the following is CloudFront content cached? 
- [ ] Region 
- [ ] Availability Zone 
- [ ] Data Center 
- [x] Edge Location 

CloudFront content is cached in Edge Locations.

## 5. Which of the following is correct? 
- [x] # of Edge Locations > # of Availability Zones > # of Regions 
- [ ] # of Availability Zones > # of Edge Locations > # of Regions 
- [ ] # of Regions > # of Availability Zones > # of Edge Locations 
- [ ] # of Availability Zones > # of Regions > # of Edge Locations 

The number of Edge Locations is greater than the number of Availability Zones, which is greater than the number of Regions. 
Further information: https://aws.amazon.com/about-aws/global-infrastructure/

## 6. What is an AWS region? 
- [x] A region is a geographical area divided into Availability Zones. Each region contains at least two Availability Zones. 
- [ ] A region is an independent data center, located in different countries around the globe. 
- [ ] A region is a subset of AWS technologies. For example, the Compute region consists of EC2, ECS, Lambda, etc. 
- [ ] A region is a collection of Edge Locations available in specific countries. 

A region is a geographical area divided into Availability Zones. Each region contains at least two Availability Zones. 
Further information: 
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html#concepts-regions-availability-zones


## 7. What does an AWS Region consist of?
- [x] A distinct location within a geographic area designed to provide high availability to a specific geography.
- [ ] A collection of databases that can only be accessed from a specific geographic region.
- [ ] A collection of data centers that is spread evenly around a specific continent.
- [ ] A console that gives you a quick, global picture of your cloud computing environment.

Each region is a separate geographic area. Each region has multiple, isolated locations known as Availability Zones. 
Further information: https://aws.amazon.com/about-aws/global-infrastructure/
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html

## 8. Which statement best describes Availability Zones?

- [ ] Two zones containing compute resources that are designed to automatically maintain synchronized copies of each other's data.
- [ ] Restricted areas designed specifically for the creation of Virtual Private Clouds.
- [X] Distinct locations from within an AWS region that are engineered to be isolated from failures.
- [ ] A Content Distribution Network used to distribute content to users.

An Availability Zone (AZ) is a distinct location within an AWS Region. Each Region comprises at least two AZs. 
Further information: https://aws.amazon.com/about-aws/global-infrastructure/

## 9. Which of the below are storage services in AWS? (Choose 2)
- [X] S3
- [ ] VPC
- [X] EFS
- [ ] EC2

S3 and EFS both provide the ability to store files in the cloud. EC2 provides compute, and is often augmented with other storage services. VPC is a networking service. 
Further information: https://aws.amazon.com/efs/
https://aws.amazon.com/s3/https://aws.amazon.com/ec2/
https://aws.amazon.com/vpc/

## 10. What is an Amazon VPC?
- [x] Virtual Private Cloud
- [ ] Virtual Public Compute
- [ ] Virtual Public Cloud
- [ ] Virtual Private Compute

VPC stands for Virtual Private Cloud. 
Further information: 
https://aws.amazon.com/vpc/

## 11. Which of the following are a part of AWS’ Network and Content Delivery services? (Choose 2)
- [x] VPC
- [x] Cloudfront
- [ ] RDS
- [ ] EC2

VPC allows you to provision a logically isolated section of the AWS where you can launch AWS resources in a virtual network. Cloudfront is a fast, highly secure and programmable content delivery network (CDN). EC2 provides compute resources while RDS is Amazon's Relational Database System. 
Further information: 
https://aws.amazon.com/vpc/
https://aws.amazon.com/cloudfront/
https://aws.amazon.com/ec2/
https://aws.amazon.com/rds/

## 12. An AWS VPC is a component of which group of AWS services?
- [x] Networking Services
- [ ] Global Infrastructure
- [ ] Database Services
- [ ] Compute Services

A Virtual Private Cloud (VPC) is a virtual network dedicated to a single AWS account. 
It is logically isolated from other virtual networks in the AWS cloud, providing compute resources with security and robust networking functionality. 
Further information: 
https://docs.aws.amazon.com/gettingstarted/latest/awsgsg-intro/gsg-aws-compute-network.html

