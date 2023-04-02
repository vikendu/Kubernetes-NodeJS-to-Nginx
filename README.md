# Kubernetes-NodeJS-to-Nginx

## Architecture
![image](https://user-images.githubusercontent.com/18619872/229292808-e3577e1d-6ed5-48db-856c-5c965b05e05e.png)

## Install minikube, kubectl & virtualisation tool(like vmware/virtual box/docker)
1. `minikube start`

## The required images are uploaded on my Docker hub:  
<`cd` into the repo dir>
1. `kubectl apply -f k8s-web-to-ngnix.yaml -f nginx.yaml` will get you up & running
2. `minikube service k8s-web-to-ngnix` to open the webpage in default browser
3. `/nginx` endpoint will get you to nginx pod from homepage
4. `kubectl delete -f k8s-web-to-ngnix.yaml -f nginx.yaml` will delete the pods.
