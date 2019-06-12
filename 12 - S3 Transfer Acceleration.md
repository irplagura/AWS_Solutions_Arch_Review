## What is S3 Transfer Acceleration
* S3 Transfer Acceleration utilises the **CloudFront Edge Network** to accelerate your uploads to S3. 
* Instead of uploading directly to your S3 bucket, you can use a distinct URL to upload directly to an edge location which will then transfer that file to S3. 
* You will get a distinct URL to upload to 
  * acIoudguru.s3-accelerate.amazonaws.com 

![Transfer Acceleration](https://github.com/irplagura/AWS_Solutions_Arch_Review/blob/master/AWS%20S3%20-%20Transfer%20Acceleration.JPG)

* S3 Transfer acceleration tool
https://s3-accelerate-speedtest.s3-accelerate.amazonaws.com/en/accelerate-speed-comparsion.html


*Enabled at Advanced Setting
Transfer Acceleration
