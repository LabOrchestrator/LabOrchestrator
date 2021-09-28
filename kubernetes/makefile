build:
	kubectl kustomize > lab_orchestrator.yaml

deploy:
	kubectl apply -f lab_orchestrator.yaml

restart-api:
	kubectl rollout restart -n lab-controller deployment lab-controller-api-deployment
