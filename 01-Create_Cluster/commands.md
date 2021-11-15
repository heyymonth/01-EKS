eksctl create cluster --name hemant-personal-cluster --fargate

eksctl create cluster -f cluster.yaml

eksctl delete cluster --name hemant-personal-cluster

kubectl describe configmap -n kube-system aws-auth