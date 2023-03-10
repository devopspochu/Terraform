# Terraform
AWS Environment
You will need access to an AWS environment with permissions to create resources in EC2, S3, and IAM. I recommend creating a throwaway account just for this course. The exercises have been tested with AWS region us-east-1. The input variable aws_region has us-east-1 set as the default, but you can supply a different region if you prefer. Generally, the exercises should work in any region that has at least three availability zones and an Amazon Linux 2 AMI.

You will need to generate an AWS access key to run through the exercises. You can do this through the IAM console in a browser (hint: it's under security credentials for your user) by following the official AWS docs. I'd recommend assigning the AdministratorAccess policy to your user to give you permissions to do everything in the account. Also, enable 2FA for the user account!
