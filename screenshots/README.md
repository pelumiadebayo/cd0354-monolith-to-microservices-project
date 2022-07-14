# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed

![pushed containers](./images/docker.PNG)

* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)

![pushed containers](./images/travis2.PNG)

* Travis CI showing a successful build and deploy job

![successful build](./images/buildpipeline.PNG)

![successful build log](./images/buildlog.PNG)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
![Kubernetes pods](./images/runpod.PNG)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
![Kubernetes services](./images/service.PNG)

* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
![Kubernetes hpa](./images/hpa.PNG)

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
![Kubernetes logs](./images/backendlog.PNG)

