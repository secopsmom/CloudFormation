# Overview
This set of yaml files can be used to collect GuardDuty event logs and send them to a centralized S3 bucket.
## Base Stack
Deploy this as a single stack within your Master GuardDuty account in us-east-1. This will create the IAM Role, Policy, and S3 Bucket.
## GD Stack
Recommend deploying as a StackSet to each region where Master and Member accounts are enabled.
## Useful Links
Link on enabling and [managing Member GuardDuty Accounts](https://aws.amazon.com/blogs/security/how-to-manage-amazon-guardduty-security-findings-across-multiple-accounts/)
