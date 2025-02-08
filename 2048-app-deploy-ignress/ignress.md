# Ignress 

- In Amazon EKS (Elastic Kubernetes Service), an Ingress is an API object that manages external access to services in a Kubernetes cluster, typically HTTP and HTTPS traffic.
- It provides HTTP routing, SSL/TLS termination, and other routing functionalities like load balancing to services within the cluster.

# Key Concepts of Ingress in EKS:

- Ingress Resource: It defines how HTTP(S) traffic should be routed to services within your Kubernetes cluster. It maps URLs and hosts to backend services.

- Ingress Controller: It is responsible for fulfilling the Ingress resource by managing a load balancer. There are multiple controllers you can use with EKS, including:

    - AWS ALB Ingress Controller: It integrates with AWS Application Load Balancers (ALBs), automatically creating an ALB when an Ingress resource is created.
    - NGINX Ingress Controller: This controller runs an NGINX proxy that manages the routing of traffic to your services.

- TLS/SSL Termination: Ingress can manage SSL/TLS certificates and handle encryption termination for secure communication.

- Routing Traffic: You can define rules in the Ingress to route traffic based on the hostname, path, or other HTTP attributes.

# Setting up an Ingress Controller on EKS:

- Install an Ingress Controller: You need to deploy an Ingress controller like AWS ALB or NGINX in your cluster.

- AWS ALB Ingress Controller: It's useful when you want to automatically integrate your services with AWS ALBs.

- NGINX Ingress Controller: It’s widely used and offers more customization options.

- Create the Ingress Resource: Once the controller is set up, you can define the Ingress resources to control the traffic routing
