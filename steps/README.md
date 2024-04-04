1. 
```bash
$ kubectl apply -f nginx-dep.yaml
```
1. 
```bash
$ kubectl apply -f nginx-configmap.yaml
```
1. 
```bash
$ kubectl apply -f nginx-svc.yaml
```
1. 
```bash
$ kubectl apply -f app-1-dep.yaml
```
1. 
```bash
$ kubectl apply -f app-1-svc.yaml
```
1. 
```bash
$ kubectl apply -f app-1-ingress.yaml
```
1. 
```bash
$ kubectl apply -f app-2-dep.yaml
```
1. 
```bash
$ kubectl apply -f app-2-svc.yaml
```
1. 
```bash
$ kubectl apply -f app-2-ingress.yaml
```
1. 
```bash
$ minikube -p ensf400 addons enable ingress
$ curl http://$(minikube ip -p ensf400)/
$ kubectl apply -f nginx-ingress.yaml
```