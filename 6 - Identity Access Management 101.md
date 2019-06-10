### What is IAM
* Identity and Access Management
* IAM allows you to manage users and their level of access to the AWS 
Console. 
* It is important to understand IAM and how it works, both for the exam and for administrating a company's AWS account in real life. 


### Key Features of IAM 
#### Identity Access Management (IAM) offers the following features; 
* Centralised control of your AWS account 
* Shared Access to your AWS account 
* Granular Permissions 
* Identity Federation (including Active Directory Faybook, Linkedin etc) 
* Multifactor Authentication 
* Provide temporary access for users/devices and services where necessary 
* Allows you to set up your own password rotation policy 
* Integrates with many different AWS services 
* Supports PCI DSS Compliance 



### Key Terminology
**1. Users** 
End Users such as people,  employees of an organization etc. 

**2. Groups** 
A collection Of users. Each user in the group will inherit the permissions Of the group. 

**3. Policies**
Polices are made up Of documents, called Policy documents. 
These documents are in a format called **JSON** and they give permissions as to what a User/Group/Ro1e is able to 
do. 

**4. Roles**
You create roles and then assign them to AWS Resources. 


# Exam Tips
## What Have We Learnt So Far? 
* **IAM is universal**. It does not apply to regions at this time. 
* The "root account" is simply the account created when first setup your AWS account. It has complete Admin access. 
* New Users have NO permissions when first created. 
* New Users are assigned Access Key ID Sec Access Keys when first created. 
* **These are not the same as a password.** You cannot use the Access key ID & Secret Access Key to Login in to the console. You can use this 
to access AWS via the APIs and Command Line, however. 
* You only get to view these once. If you lose them, you have to regenerate them. So, save them in a secure location. 
* Always setup Multifactor Authentication on your root account. 
* You can create and customise your own password rotation policies. 

