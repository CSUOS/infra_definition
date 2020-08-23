```bash
kubectl create namespace argocd
kubectl -n argocd apply -f install.yaml
kubectl -n argocd apply -f ingress.yaml

./argocd-linux-amd64 login argo.csuos.ml --grpc-web
./argocd-linux-amd64 account update-password
```