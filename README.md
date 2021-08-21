# wordpress-docker

This is for tutorial, use dedicated database instead of database containerized

## Docker

```bash
docker-compose up --scale wordpress=2 -d
```

## Kubernetes

### MySQL

- Persistence Volume Claims
- Service & Deployment

### WordPress

- Persistence Volume Claims
- Service & Deployment
- Horizontal Pod Autoscaler

### How To

```bash
echo -n "password" | base64
echo -n "user" | base64
...
# add value to secret.yaml file
kubectl apply -f kubernetes/
```
