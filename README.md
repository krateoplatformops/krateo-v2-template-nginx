# Krateo V2 Template NGINX

This is a template used to deploy NGINX.

## How to install

```sh
kubectl create ns nginx-system
kubectl apply -f https://raw.githubusercontent.com/krateoplatformops/krateo-v2-template-nginx/refs/heads/main/compositiondefinition.yaml
```

### With *Krateo Composable Portal*

#### With custom form

```sh
kubectl apply -f https://raw.githubusercontent.com/krateoplatformops/krateo-v2-template-nginx/refs/heads/main/customform.yaml
```