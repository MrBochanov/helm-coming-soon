# helm-coming-soon

Simple helm-chart for implementing "coming soon" page.
Based on [zedtux/docker-coming-soon](https://hub.docker.com/r/zedtux/docker-coming-soon/)

For ease of verification, Ingress configured with http port without SSL support

Install:
```
    helm install coming-soon-release helm-coming-soon/

```  
Upgrade:
```
    helm upgrade coming-soon-release helm-coming-soon/

```  