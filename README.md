# devops

http://localhost:8001/devops/test

kubectl create -f devops.yaml
kubectl expose deployment devops --type="LoadBalancer"
kubectl delete -f devops.yaml