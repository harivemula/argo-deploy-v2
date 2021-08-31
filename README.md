# argo-deploy-v2

## Install Nginx Ingress with helm:

```
helm install nginx-ingress-nginx ingress-nginx/ingress-nginx -n nginx-ingress --set controller.extraArgs.enable-ssl-passthrough="",podSecurityPolicy.enabled=true
```
