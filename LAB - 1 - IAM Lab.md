https://acloud.guru/course/aws-certified-solutions-architect-associate/learn/iam-s3/create-bucket/watch


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


