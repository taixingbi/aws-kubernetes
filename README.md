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

### run app

#### hello world
https://kubernetes.io/docs/tutorials/hello-minikube/

```
kubectl get deployments
kubectl get events
kubectl config view
kubectl get services
kubectl delete service hello-node
kubectl delete deployment hello-node
```



### reference
```
https://kubernetes.io/docs/setup/
https://www.youtube.com/watch?v=p6xDCz00TxU
https://www.youtube.com/watch?v=SsUnPWp5ilc
```
