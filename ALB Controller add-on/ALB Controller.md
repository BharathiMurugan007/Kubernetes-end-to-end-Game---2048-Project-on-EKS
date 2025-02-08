# ALB CONTROLLER

- The AWS Load Balancer Controller (ALB Controller) is a Kubernetes controller used to manage AWS Application Load Balancers (ALB).
- Network Load Balancers (NLB) for Kubernetes services running in Amazon Elastic Kubernetes Service (EKS) or self-managed Kubernetes clusters on AWS. 
- It automatically provisions ALBs and NLBs to route external traffic to Kubernetes applications.

# How AWS ALB Controller Works

- You deploy the AWS Load Balancer Controller as a Kubernetes Deployment.
- It watches for Kubernetes Ingress and Service resources.
- When a new Ingress is created:
    - The controller provisions an ALB.
    - ALB routes traffic to Kubernetes Pods via Target Groups.
- When a Service of type LoadBalancer is created:
   - The controller provisions an NLB (for TCP/UDP traffic).
   - The NLB forwards traffic to Kubernetes nodes or Pods.
