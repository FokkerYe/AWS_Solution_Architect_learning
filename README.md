# AWS_Solution_Architect_learning


![ASW simple](https://www.learnquest.com/assets/images/aws-machine-learning-engineer-certification-path.png)

# AWS IAM (Identity and Access Management)

IAM stands for Identity and Access Management, and it is a global service within AWS. By default, there is a Root Account created, which has full administrative access to all AWS resources.

## IAM Users

IAM users are individual accounts created within your AWS environment. These users can have their own username and password or access keys for programmatic access. An important feature of IAM users is that they can belong to multiple IAM groups.

## IAM Policies

IAM policies are used to define and manage the permissions of IAM users and groups. These policies specify what actions users and groups are allowed or denied regarding AWS resources.

### Assigning Policies

IAM policies can be assigned to either IAM users or IAM groups. Policies are typically written in JSON format, and they consist of statements that define the allowed or denied permissions.

**Example IAM Policy JSON:**

```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::example-bucket/"
    },
    {
      "Effect": "Deny",
      "Action": "ec2:TerminateInstances",
      "Resource": ""
    }
  ]
}


IAM USER = Identity and Access Management, Global Service, Root account => Created by Default

User, Groups => User can belong to Multiple Groups.

IAM POLICIES => User or Groups can be assigned to define the permissions of the users.



