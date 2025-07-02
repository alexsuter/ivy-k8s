# Axon Ivy Engine Standard

## System Database

```
kubectl apply -f postgres.yaml
```

```
kubectl delete -f postgres.yaml
```

## Axon Ivy Engine

```
kubectl apply -f ivy.yaml
```

```
kubectl delete -f ivy.yaml
```

## Access with port forwarding

```
kubectl port-forward service/ivy 8080:8080
```

Open browser http://localhost:8080
