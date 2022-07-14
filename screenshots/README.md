# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed
![pushed containers](C:\Users\pelumi.adebayo\Pictures\docker.PNG)

* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)
![pushed containers](C:\Users\pelumi.adebayo\Pictures\travis2.PNG)

* Travis CI showing a successful build and deploy job
![successful build](C:\Users\pelumi.adebayo\Pictures\buildpipeline.PNG)
![successful build log](C:\Users\pelumi.adebayo\Pictures\buildlog.PNG)


## Kubernetes
* To verify Kubernetes pods are deployed properly
```bash
kubectl get pods
```
![Kubernetes pods](C:\Users\pelumi.adebayo\Pictures\runpod.PNG)

* To verify Kubernetes services are properly set up
```bash
kubectl describe services
```
![Kubernetes pods](C:\Users\pelumi.adebayo\Pictures\service.PNG)

* To verify that you have horizontal scaling set against CPU usage
```bash
kubectl describe hpa
```
![Kubernetes pods](C:\Users\pelumi.adebayo\Pictures\hpa.PNG)

* To verify that you have set up logging with a backend application
```bash
kubectl logs {pod_name}
```
![Kubernetes pods](C:\Users\pelumi.adebayo\Pictures\backendlog.PNG)

