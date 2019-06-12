## Using Versioning With S3 
https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/iam-s3/s3-versioning/watch

* Stores all versions of an object (including all writes 
and even if you delete an object) 
* Great backup tool. 
* Once enabled, Versioning **cannot disabled, only suspended**. 

* Integrates with Lifecycle rules 
* Versioning's MFA Delete capability, which uses multi-factor authentication, can be used to provide an additional layer of security. 

LAB 
* Create a new S3 bucket
* Upload a file, turn on Versioning in Bucket Properties
* You can only Disable or SUSPEND Versioning
* Uploading a new version of the file (same name),  will result in properties like public permission resets to default.

* Deleting a file will put only a **Delete Marker**,  and can only be restored by **deleting the Delete Marker** (Action Tab)


# Exam Tips 
* Stores all versions of an object (including all writes and even if you delete an object) 
* Great backup tool. 
* Once enabled, Versioning canno b disabled, only suspended. 
* Integrates with Lifecycle rules 
* Versioning's MFA Delete capability, which uses multi-factor 
authentication, can be used to provide an additional layer of security. 
