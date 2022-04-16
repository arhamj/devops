up:
	kubectl apply -f mongo-secret.yml
	kubectl apply -f mongo-deployment.yml
	kubectl apply -f mongo-configmap.yml
	kubectl apply -f mongo-express-deployment.yml

down:
	kubectl delete -f ingress.yml;
	kubectl delete -f mongo-express-deployment.yml;
	kubectl delete -f mongo-configmap.yml;
	kubectl delete -f mongo-deployment.yml;
