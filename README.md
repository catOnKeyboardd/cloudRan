List of Commands:<br />
<br />
Deletion:<br />
kubectl delete deployment hello-app<br />
kubectl delete service hello-app<br />

Step by Step:<br />
minikube start<br />
kubectl create deployment hello-app --image=gcr.io/google-samples/hello-app:2.0<br />
kubectl expose deployment hello-app --type=NodePort --port=8080<br />
minikube service hello-app --url<br />
Curl <br />

Checking Commands:<br />
kubectl get deployments<br />
kubectl get pods<br />
kubectl get services<br />

After Clone:<br />
minikube start<br />
minikube service hello-app --url<br />
Curl <br />

