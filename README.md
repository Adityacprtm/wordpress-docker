# wordpress-docker

## Docker

```bash
docker-compose up --scale wordpress=2 -d
```

## Kubernetes

```bash
echo -n "password" | base64
echo -n "user" | base64
# add value to secret.yaml file
kubectl apply -f kubernetes/
```
