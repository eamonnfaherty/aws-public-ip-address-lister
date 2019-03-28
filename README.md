This is a code sample showing how to use https://github.com/arkadiyt/aws_public_ips within an 
AWS CodeBuild Project.

aws_public_ips will list the public ip addresses present in your AWS account for the following 
services:

- APIGateway
- CloudFront
- EC2 (and as a result: ECS, EKS, Beanstalk, Fargate, Batch, & NAT Instances)
- ElasticSearch
- ELB (Classic ELB)
- ELBv2 (ALB/NLB)
- Lightsail
- RDS
- Redshift