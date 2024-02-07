## Fire up a container

```
kubectl run my-shell --rm -i --tty --image nginx -- bash
```

## Create a secret

```
kubectl create secret generic my-secret -n my-namespace --from-literal=my-key=my-value
```

