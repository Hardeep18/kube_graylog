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
graylog-service.yaml
```
```
graylog-deployment.yaml
```
```
mongo-service.yaml
```
```
mongo-deployment.yaml
```

### 2. Forward port 9000 
```
 kubectl port-forward graylog-0 9000:9000
```
