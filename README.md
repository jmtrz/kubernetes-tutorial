Please run the following commands in succession to deploy the following files
1. `kubectl apply -f mongo-secret.yaml`
2. `kubectl apply -f mongo.yaml`
3. `kubectl apply -f mongo-configmap.yaml`
4. `kubectl apply -f mongo-express.yaml`
5. `kubectl get services`                          _// get the deployed services which has a load balancer_
6. `minikube service <mongo_express_service_name>` _// open up a browser for mongo-express_
