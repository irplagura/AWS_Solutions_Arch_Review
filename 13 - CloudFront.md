## What is CloudFront
* A content delivery network (CDN) is a system of distributed servers (network) that deliver webpages and other web content to a user based on the geographic locations 
of the user, the origin of the webpage, and a content delivery server. 

## Key Terminology
* Edge Location - This is the location where content will be cached. This is separate to an AWS Region/AZ. 
* Origin - This is the origin of all the fileythat the CDN will distribute. This can be an S3 Bucket, an EC2 Instance, an Elastic Load Balancer, or 
Route53. 
* Distribution - This is the name given the CDN which consists of a collection of Edge Locations. 

