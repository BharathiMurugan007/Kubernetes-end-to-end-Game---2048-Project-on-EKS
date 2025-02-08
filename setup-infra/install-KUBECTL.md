# KUBECTL 
- kubectl is the command-line tool for interacting with Kubernetes clusters.
- It allows you to manage Kubernetes objects, deploy applications, inspect and troubleshoot clusters, and automate various tasks.
# Install KUBECTL

       curl -o kubectl https://amazon-eks.s3.us-west-2.amazonaws.com/1.19.6/2021-01-05/bin/linux/amd64/kubectl
       chmod +x ./kubectl
       sudo mv ./kubectl /usr/local/bin
       kubectl version --short --client
