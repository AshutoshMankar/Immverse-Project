# Immverse DevOps CI/CD Assignment

## Architecture

Developer
→ GitHub
→ Jenkins
→ Docker Build
→ Docker Hub
→ Kubernetes Deployment
→ Prometheus
→ Grafana

## Tools Used

* GitHub
* Jenkins
* Docker
* AWS EC2
* Kubernetes (Kind)
* Prometheus
* Grafana

## Application URL

http://13.127.60.67:8081

## Docker Image

ashuman/immverse-app:6

## Kubernetes Resources

### Deployment

* Deployment Name: immverse-app
* Replicas: 2

### Service

* Service Name: immverse-service
* Type: NodePort
* Target Port: 3000

## Deliverables

* Dockerfile
* Jenkinsfile
* deployment.yaml
* service.yaml
* Running Application
* GitHub Repository
