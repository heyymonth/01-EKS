# Create EKS cluster
```shell
eksctl create cluster --name hemant-personal-cluster --fargate

eksctl create cluster --name my-cluster --region region-code
```

# Create EKS cluster using yaml

**Refer to cluster.yaml file**
```zsh
eksctl create cluster -f cluster.yaml
```

# Delete EKS cluster
```yaml
eksctl delete cluster --name hemant-personal-cluster
```

# Describe configmaps
```bash
kubectl describe configmap -n kube-system aws-auth
```
