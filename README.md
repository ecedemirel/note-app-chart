# Guide

Run below at the root directory:

```
helm install note-app-chart-release .
```

<br/>

If you want to remove:

```
helm uninstall note-app-chart-release 
```

<br/>

If you cannot access, run below:

```
minikube service note-app-chart-release
```
or
```
kubectl port-forward svc/note-app-chart-release 30080:80  
```