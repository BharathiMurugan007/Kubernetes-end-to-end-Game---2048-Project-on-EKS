# Service

- Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service that allows you to run Kubernetes applications on AWS without managing the control plane or the underlying infrastructure.
- It integrates with AWS networking, security, and monitoring services, making it easier to deploy, manage, and scale containerized applications.

# Key Features of EKS:

- Managed Kubernetes Control Plane:

  AWS handles the Kubernetes master nodes, including availability, scalability, and security patches.

- Integration with AWS Services:

  Works with IAM, VPC, Load Balancers (ALB/NLB), CloudWatch, and ECR for better security, networking, and monitoring.

- Auto Scaling with Cluster Autoscaler & Karpenter:

  Scales nodes dynamically based on demand.

- Support for Fargate & EC2:

   You can run workloads on Amazon EC2 (self-managed nodes) or AWS Fargate (serverless mode).

- Multi-Cluster & Multi-Region Deployment:

   Easily deploy workloads across multiple regions and clusters.

- High Availability & Security:

   EKS supports multi-AZ control plane and integrates with AWS security services like IAM, KMS, and Secrets Manager.

