** Suggest to use US East (N. Virginia) Region

* Login to AWS console
* Services -> Security Identity and Compliance
* Select IAM

* Sign-in Link:
https://xxxxxxxxx.signin.aws.amazon.com/console
* You can Customize and create an account alias for this 

* Set each Security Status:
- [x] *Automatically* deletes your root access keys
- [x] Activate MFA
- [x] Create Individual IAM users
- [x] Use groups to assign permissions
- [x] Apply an IAM password policy

* MFA device to assign
- [x] Virtual MFA Device
- [ ] U2F Security key
- [ ] Other Hardware MFA device

* Create Individual IAM users
Manage User -> Add User -> usernamexxx
* Select AWS type
Programmatic Access - enables access key id and secret key access
AWS Management Console Access

* Create Group and assign to Policy
ie. New Group name is: Developers and assign to **AdministratorAccess**  (JobFunction) policy
Create Group


# Exam Tips
## What Have We Learnt So Far? 
* **IAM is universal**. It does not apply to regions at this time. 
* The "root account" is simply the account created when first setup your AWS account. It has complete Admin access. 
* New Users have NO permissions when first created. 
* New Users are assigned Access Key ID Sec Access Keys when first created. 
* **These are not the same as a password.** You cannot use the Access key ID & Secret Access Key to Login in to the console. You can use this 
to access AWS via the APIs and Command Line, however. 
* You only get to view these once. If you lose them, you have to regenerate them. So, save them in a secure location. 
