List of Commands:

Deletion:
kubectl delete deployment hello-app
kubectl delete service hello-app

Step by Step:
minikube start
kubectl create deployment hello-app --image=gcr.io/google-samples/hello-app:2.0
kubectl expose deployment hello-app --type=NodePort --port=8080
minikube service hello-app --url
Curl 

Checking Commands:
kubectl get deployments
kubectl get pods
kubectl get services
kubectl get deployments
kubectl get pods
kubectl get services

After Clone:
minikube start
minikube service hello-app --url
Curl 

