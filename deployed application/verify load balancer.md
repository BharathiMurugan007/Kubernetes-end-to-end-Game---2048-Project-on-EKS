# verify load balancer

- verify that load balancer is created or not and there are atleast 2 replicas have or not.
- verify that depployment are running or not.

## command to verify
```
kubectl get deployment -n kube-system aws-load-balancer-controller
```
