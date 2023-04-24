# Hello!'

## Привет!'

1. Install kyverno

```sh
helm repo add kyverno https://kyverno.github.io/kyverno
helm repo update kyverno
helm install kyverno kyverno/kyverno --version "2.7.2" --namespace kyverno --create-namespace 
```
