# aws-cloud-engineering-learning
This repository is for my learning of AWS services in regard to the AWS Solutions Architect Associate Certification


## EC2 Web Server Deployment

An Amazon EC2 instance running Amazon Linux was deployed using the AWS Management Console. SSH access was configured using a key pair and Security Groups were configured to allow HTTP and SSH traffic. Nginx was installed, started, and configured to launch automatically on system boot.

Key Concepts Learned:

* Amazon EC2
* Security Groups
* SSH Authentication
* Linux Administration
* Nginx Web Server
* Elastic IP Addresses

## S3 Static Website Hosting

An Amazon S3 bucket was configured for static website hosting and used to host a simple HTML webpage. Public access was configured through a bucket policy and website hosting settings. Additional security controls including encryption, versioning, access logging, and lifecycle policies were implemented.

Key Concepts Learned:

* Amazon S3
* Static Website Hosting
* Bucket Policies
* SSE-S3 Encryption
* SSE-KMS Encryption
* Object Versioning
* Lifecycle Policies
* Access Logging

## Identity and Monitoring

IAM users and groups were configured following the principle of least privilege. AWS CLI credentials were configured using IAM access keys. AWS CloudTrail was enabled to record API activity and provide account-level auditing.

Key Concepts Learned:

* AWS IAM
* IAM Groups
* IAM Policies
* AWS CLI
* AWS CloudTrail
* Auditing and Monitoring
