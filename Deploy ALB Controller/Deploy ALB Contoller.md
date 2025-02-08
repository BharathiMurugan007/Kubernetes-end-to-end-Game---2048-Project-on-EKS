# Deploy ALB controller

This Helm Chart will create for the actual controller and it will use this service account for running the pod.

## Add helm repo
```
helm repo add eks https://aws.github.io/eks-charts
```

## Update the repo
```
helm repo update eks
```
## Install
```
helm install aws-load-balancer-controller eks/aws-load-balancer-controller -n kube-system \
  --set clusterName=my-cluster \
  --set serviceAccount.create=false \
  --set serviceAccount.name=aws-load-balancer-controller \
  --set region=us-east-1 \
  --set vpcId=vpc-060862115ebof134b
```
# Verify that the deployments are running
```
kubectl get deployment -n kube-system aws-load-balancer-controller
```
