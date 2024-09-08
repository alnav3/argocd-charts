# in case of first installation in a new server, remember to run this command first:
kubectl create secret generic helm-secrets-private-keys --from-file=key.txt=assets/age/key.txt
being assets/age/key.txt the location of the private key file in your computer
