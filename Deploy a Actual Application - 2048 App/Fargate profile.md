# Fargate Profile

- AWS EKS (Elastic Kubernetes Service), a Fargate Profile is used to run Kubernetes pods on AWS Fargate, a serverless compute engine for containers. 
- It allows you to run your workloads without managing EC2 instances.

# Key Features of a Fargate Profile

- Serverless – No need to provision or manage EC2 instances.
- Cost-Optimized – Pay only for the vCPU and memory used by running pods.
- Pod-Level Isolation – Each pod runs in its own isolated environment.
- Security – Integrates with IAM and AWS VPC for fine-grained access control.
- Simplifies Scaling – No need to manually scale nodes; Fargate scales automatically based on pod demand.

# How a Fargate Profile Works
- When you create a Fargate Profile, you specify:
    A namespace and/or labels that define which pods should run on Fargate.
    The IAM role used by Fargate to access AWS services.
    The subnets where Fargate should launch the pods.
- Whenever a pod matching the profile's selectors is scheduled, EKS automatically launches it on AWS Fargate instead of an EC2 worker node.
