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




```
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

```


IAM USER
IAM =Identity and Access Management, Global Service
Root account=> Created by Default
User,Groups
User can belong to Multiople Groups.

IAM POLICIES
User or Groups can be assigned
Define the permissions of the users

# My AWS Learning Journey

## Amazon IAM (Identity and Access Management):

Learned about managing users, groups, and permissions using IAM. Explored best practices for securing AWS resources.

## Amazon EC2 (Elastic Compute Cloud):

Understood the basics of launching and managing virtual servers in the cloud. Explored different instance types and use cases.

## Amazon VPC (Virtual Private Cloud):

Explored the concepts of virtual networks, subnets, route tables, and security groups to create isolated and secure environments in the cloud.

## Amazon S3 (Simple Storage Service):

Learned about object storage, buckets, and various storage classes. Explored how to store and retrieve data securely.

## AWS Lambda:

Explored serverless computing by creating and deploying functions without managing servers. Understood event-driven architecture.

## Amazon RDS:

Learned about managed relational databases, including setup, configuration, and maintenance of databases in the cloud.

## Amazon ECR (Elastic Container Registry):

Explored containerization by managing and storing Docker images securely.

## Amazon EKS (Elastic Kubernetes Service):

Understood Kubernetes orchestration for containerized applications and how to manage them on AWS.

## AWS CodeDeploy:

Learned about automated deployment of applications to various compute services, ensuring reliability and scalability.

## AWS CodePipeline:

Explored continuous integration and continuous delivery (CI/CD) pipelines to automate software release processes.

## Amazon CloudWatch:

Understood monitoring and observability by collecting and visualizing logs, metrics, and events from AWS resources.

## Amazon CloudFormation:

Explored infrastructure as code (IaC) by creating and managing AWS resources using templates.

## AWS Elastic Load Balancing:

Learned about distributing incoming application traffic across multiple targets to ensure high availability and fault tolerance.

## AWS CloudTrail:

Explored logging and monitoring of AWS account activity, providing visibility into actions taken by users and resources.

## AWS Elastic Beanstalk:

Understood platform as a service (PaaS) by deploying and managing applications without dealing with the underlying infrastructure.

## AWS Step Functions:

Explored serverless orchestration service for building workflows using visual workflows.

## AWS Config:

Learned about tracking and managing AWS resource configurations and changes over time.

---

This summary captures the key AWS services and concepts you've explored during your learning journey.




