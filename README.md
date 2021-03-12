# piHole-fargate-cloudformation

  This template deploys piHole to an AWS Fargate Cluster on user-defined VPC and Subnets. Container definition is pulled from the public Docker image for piHole (https://hub.docker.com/r/pihole/pihole/). An ECS Service ensures piHole continues to run. Logging is captured within CloudWatch. 

## Important!

  You'll also need to verify a task execution role for ECS is setup (see https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_execution_IAM_role.html)

