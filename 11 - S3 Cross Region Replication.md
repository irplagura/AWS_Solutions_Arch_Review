## Lab
https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/iam-s3/s3-crr/watch

* S3 Bucket
* Management -> Replication Tab
* Add a Rule
* **Requires Versioning** Enabled

![Cross Region Replication](https://github.com/irplagura/AWS_Solutions_Arch_Review/blob/master/S3%20-%20replication%20Rule.JPG)

* When Cross region replication is enabled,  Existing Objects in source bucket are not added. Need to re-upload the file or only newer files are replicated.
* Delete markers are not replicated
* Deleting a file in the source will not eventually remove the file in the replicated 

# Exam Tips
* Versioning must be enabled on both the source and destination buckets. 
* Regions must be unique. 
* Files in an existing bucket are not epli ated automatically. 
* All subsequent updated files will be replicated automatically. 
* Delete markers are not replicated. 
* Deleting individual versions or delete markers will not be replicated. 
