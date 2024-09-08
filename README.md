# IMPORTANT! remember to use this command in case of complete reset of the server
kubectl -n argocd create secret generic helm-secrets-private-keys --from-file=key.txt=assets/age/key.txt
