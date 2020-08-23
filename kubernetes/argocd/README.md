```bash
kubectl create namespace argo
kubectl -n argo apply -f install.yaml
kubectl -n argo apply -f ingress.yaml

./argocd-linux-amd64 login argo.csuos.ml --grpc-web

```