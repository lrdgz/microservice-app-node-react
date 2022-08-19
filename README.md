# microservice-app-node-react
Simple example using microservice with node and React


# DOCKER COMMANDS

- docker build .
- docker push  [conainer_name]
- docker run [container_id]
- docker build -t [container_name] .
- docker run [container_name]
- docker run -it [container_name] sh
- docker logs [container_id]


# KUBERNETES (Minikube)
- minikube start
- minikube addons enable ingress
- kubectl get pods -n ingress-nginx
- kubectl get po -A
- kubectl apply -f .\[file].yml
- kubectl apply -f .
- kubectl get pods
- kubectl exec -it [pod_name] [cmd] sh
- kubectl logs [pod_name]
- kubectl delete pod [pod_name]
- kubectl delete deployment [deploy_name]
- kubectl describe deployment [deploy_name]
- kubectl rollout restart deployment [deploy_name]
- kubectl get services
- kubectl describe service [service_name]



- kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.30.0/deploy/static/mandatory.yaml
- kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/nginx-0.30.0/deploy/static/provider/cloud-generic.yaml