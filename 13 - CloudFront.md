## What is CloudFront
* A content delivery network (CDN) is a system of distributed servers (network) that deliver webpages and other web content to a user based on the geographic locations 
of the user, the origin of the webpage, and a content delivery server. 

![How CloudFront Works](https://github.com/irplagura/AWS_Solutions_Arch_Review/blob/master/AWS%20-%20CloudFront.JPG)

## Key Terminology
* Edge Location - This is the location where content will be cached. This is separate to an AWS Region/AZ. 
* Origin - This is the origin of all the fileythat the CDN will distribute. This can be an S3 Bucket, an EC2 Instance, an Elastic Load Balancer, or 
Route53. 
* Distribution - This is the name given the CDN which consists of a collection of Edge Locations. 

* Amazon CloudFront can be used to deliver your entire website, including dynamic, static, streaming, and interactive content using a global network of edge locations. 
* Request for your content are automatically routed to the **nearest edge location**, so content is delivered with the best possible performance. 

* Web Distribution - Typically used for Websites. 
* RTMP - Used for Media Streaming. 


# Exam Tips
* CloudFront is a **GlobalService**
* **Edge Location** - This is the location where content will be cached. This is separate to an AWS Region/AZ. 
* **Origin** - This is the origin of all the files that the CDN will distribute. This can be either an S3 Bucket, an EC2 Instance, an Elastic Load Balancer, or Route53. 

* **Distribution** - This is the name given the CDN which consists of a collection of Edge Locations. 
* **Web Distribution** - Typically used for Websites. 
* **RTMP**  - Used for Media Streaming. 

* Edge locations are not just READ only — you can write to them too. (ie put an object on to them.) 
* Objects are cached for the life of the **TTL (Time To Live.)** 
* You can clear cached objects, **but you will be charged**. 

## Lab
https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/iam-s3/cloudfront-lab/watch

* AWS Services -> **Networking** -> CloudFront
* CreateDistribution
* Origin -> (Existing S3 Bucket that you'll use for CDN)
* Click to create Distribution **(will take a while - ~an hour)**

* Copy the domain name in clipboard: xxxxx.cloudfront.net
so you'll use the URL instead of the s3bucket 
ie. https://xxxxx.cloudfront.net/

* **Invalidation**
  * Go to Invalidations tab and **CreateInvalidation**, and click invalidate.
  * /* will invalidate everything
  * /somefile.jpg - will only invalidate this file
  * if you hit into a scenario where files is not updating you can use this to invalidate a file/s

