# tech-talk helm chart

## Deployment
 
```bash
kubectl create namespace production
helm install tech-talk-production ./ --namespace production  -f helm_vars/production/values.yaml
```
