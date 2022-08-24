# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
* Travis CI showing a successful build and deploy job


## DockerHub showing containers that I have pushed
![image](https://user-images.githubusercontent.com/77249754/186338846-9c24b587-d0f1-45e4-8759-f2154eb4529f.png)

## Circeleci Scccessful build
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/kabeer-prog/udagram-monolith-microservices-project/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/kabeer-prog/udagram-monolith-microservices-project/tree/master)
![image](https://user-images.githubusercontent.com/77249754/186339615-acf8a92c-a4e1-4e24-a58c-688018e04ae7.png)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
