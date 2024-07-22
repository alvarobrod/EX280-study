# Declarative Resource Management 

1. Deploy an application by using Kustomize.

```
cd kustomize/

oc apply -k base/
```

2. Deploy an overlay of the application that increases the number of replicas.

```
oc apply -k overlays/production
```

  [back to main](../README.md) 
