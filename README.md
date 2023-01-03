# Learning project
## Steps to deploy:
1. minikube start -p fresh
2. cd kubernetes
3. kubectl apply -f .
4. minikube service ingress-nginx-controller -n ingress-nginx --url -p fresh
5. http://127.0.0.1:your-port/kibana to access kibana and http://127.0.0.1:your-port/getTaskAnswer to access web server