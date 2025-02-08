# EKSCTL 
- eksctl is a command-line tool for managing Amazon Elastic Kubernetes Service (EKS) clusters.
- It simplifies the process of creating, updating, and managing EKS clusters on AWS.

## Key Features of eksctl
- EKS Cluster Creation – Easily create an EKS cluster with a single command.
- Node Group Management – Add, update, and delete node groups.
- IAM Role and Security Setup – Automatically sets up necessary IAM roles and security groups.
- Fargate Support – Supports AWS Fargate for serverless Kubernetes.
- Cluster Scaling – Modify worker nodes and auto-scaling groups.
- Helm and Add-on Integration – Install Kubernetes add-ons like CoreDNS, VPC CNI, and kube-proxy.
- Cluster Deletion – Clean up EKS resources when no longer needed.


# Install EKSCTL
        curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
        sudo mv /tmp/eksctl /usr/local/bin
        eksctl version
