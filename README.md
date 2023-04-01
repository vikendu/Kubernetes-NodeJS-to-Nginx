# Kubernetes-NodeJS-to-Nginx

## Install minikube, kubectl & virtualisation tool(like vmware/virtual box/docker)
1. `minikube start`

## The required images are uploaded on my Docker hub:  
1. `kubectl apply -f k8s-web-to-ngnix.yaml -f nginx.yaml` will get you up & running
2. `minikube service k8s-web-to-ngnix` to open the webpage in default browser
3. `/nginx` endpoint will get you to nginx pod from homepage
