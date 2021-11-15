# Create EKS cluster
```yaml
eksctl create cluster --name hemant-personal-cluster --fargate
```

# Create EKS cluster using yaml

**Refer to cluster.yaml file**
```yaml
eksctl create cluster -f cluster.yaml
```

# Delete EKS cluster
```yaml
eksctl delete cluster --name hemant-personal-cluster
```

# Describe configmaps
```yaml
kubectl describe configmap -n kube-system aws-auth
```
