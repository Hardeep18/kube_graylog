# Kube_graylog_pod

# Steps to install graylog cluster 


### 1. Run graylog cluster 
```
 kubectl create -f elasticsearch-deployment.yaml
```
```
kubectl create -f elasticsearch-service.yaml
```
```
kubectl create -f graylog-service.yaml
```
```
kubectl create -f graylog-deployment.yaml
```
```
kubectl create -f mongo-service.yaml
```
```
kubectl create -f mongo-deployment.yaml
```

### 2. Forward port 9000 
```
 kubectl port-forward graylog-0 9000:9000
```
### Verify ###

```
kubectl get pods,svc

```
