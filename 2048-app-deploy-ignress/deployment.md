# Deployment 

- Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service that simplifies running Kubernetes on AWS without the need to install and manage your own Kubernetes control plane.
- Deploying applications on EKS involves multiple steps, including cluster setup, configuring networking, defining deployments, and setting up CI/CD pipelines for automation.

# Key Considerations

- IAM Roles & Policies: Use IAM roles for the EKS cluster to allow pulling from ECR and managing resources.
- Networking: Ensure the cluster is properly set up with VPC, subnets, and security groups.
- Autoscaling: Configure Horizontal Pod Autoscaler (HPA) for scaling based on CPU/memory.
- Observability: Use Prometheus & Grafana or AWS CloudWatch for monitoring.

