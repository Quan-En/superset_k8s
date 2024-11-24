follow this tutorial: https://www.digitalocean.com/community/tutorials/how-to-deploy-postgres-to-kubernetes-cluster

temp:
1. generate deployment.yaml: `helm template . --output-dir './yamls'`
2. expose url: `minikube service release-name-superset --url`