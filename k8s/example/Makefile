.PHONY: up
up:
	kaf mongo-secret.yml
	kaf mongo-deployment.yml
	kaf mongo-configmap.yml
	kaf mongo-express-deployment.yml

.PHONY: down
down:
	kdelf mongo-express-deployment.yml
	kdelf mongo-configmap.yml
	kdelf mongo-deployment.yml
	kdelf mongo-secret.yml
