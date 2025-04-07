# IMPORTANT! remember to use this command in case of complete reset of the server
kubectl -n argocd create secret generic helm-secrets-private-keys --from-file=key.txt=assets/age/key.txt
# Remember to install the smb plugin for use in the pods:
curl -skSL https://raw.githubusercontent.com/kubernetes-csi/csi-driver-smb/v1.13.0/deploy/install-driver.sh | bash -s v1.13.0 --
