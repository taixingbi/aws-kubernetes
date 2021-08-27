### steps

#### cluster 
```
aws eks  describe-cluster --name awstgeks --region us-east-2 --query cluster.status 
aws eks update-kubeconfig --name awstgeks --region us-east-2
```

#### kubectl
```
kubectl get svc
kubectl get pods 
kubectl get nodes
kubectl get nodes --watch
```

### reference
```
https://www.youtube.com/watch?v=p6xDCz00TxU
https://www.youtube.com/watch?v=SsUnPWp5ilc
```
