## By default, all newly created buckets are PRIVATE. 
* You can setup access control to your buckets using; 
  * **Bucket Policies** 
  * **Access Control Lists** 
* S3 buckets can be configured to create access logs which log all requests made to 
the S3 bucket. This can be sent to another bucket and even another bucket in another account. 


## Encryption In Transit is achieved by 
* SSL/TLS 
## Encryption At Rest (Server Side Encryption) is achieved by 
* S3 Managed Keys - SSE-S3 
* AWS Key Management Service, Managed 
Keys - SSE-KMS 
* Server Side Encryption With Customer 
Provided Keys - SSE-C 
## Client Side Encryption
* Upload an existing encrypted file to S3

https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/iam-s3/s3-security/watch

Select the individual file in S3 -> Properties -> Encryption

