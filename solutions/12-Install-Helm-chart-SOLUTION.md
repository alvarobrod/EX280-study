# Install a Helm chart

1. Deploy an application on the *helm-app* namespace by using the Helm chart "hello-world" available on the following Helm repo: https://helm.github.io/examples

```
oc new-project helm-app

helm repo add examples https://helm.github.io/examples

helm install test examples/hello-world -n helm-app

```
  [back to main](./README.md) 