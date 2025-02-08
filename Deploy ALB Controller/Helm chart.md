# Overview of Helm chart

- Helm is a package manager for Kubernetes that simplifies the deployment and management of applications using Helm Charts. 
- In AWS, Helm is widely used to deploy applications in Amazon EKS (Elastic Kubernetes Service) or other Kubernetes environments.

# Helm Chart

- A Helm Chart is a collection of YAML templates and configurations used to define, install, and manage Kubernetes applications.

## Key Components of a Helm Chart:
- Chart.yaml – Contains metadata about the chart (name, version, etc.).
- values.yaml – Defines default configuration values for the chart.
- templates/ – Contains Kubernetes YAML manifests (e.g., Deployment, Service, ConfigMap).
- requirements.yaml (optional) – Lists dependencies for the chart.
- charts/ – Directory for dependent Helm charts.

