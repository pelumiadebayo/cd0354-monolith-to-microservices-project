# Screenshots
To help review your infrastructure, please include the following screenshots in this directory::

## Deployment Pipeline
* DockerHub showing containers that you have pushed

![pushed containers](./images/docker.PNG)

* GitHub repository’s settings showing your Travis webhook (can be found in Settings - Webhook)

![pushed containers](./images/webhook.PNG)

![pushed containers](./images/travis.PNG)


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
![Kubernetes services](./images/servicediscribe.PNG)

* To verify that Kubernetes services shows a reverse proxy
```bash
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
![backend logs](./images/backendlog.PNG)

*[Final running frontend image](http://a5923ec814af14e0c9a8a4be37c204f6-1142240796.us-east-1.elb.amazonaws.com/)

![Running project](./images/runingproject.PNG)
