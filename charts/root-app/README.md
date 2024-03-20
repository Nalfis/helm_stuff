# apply manifest into kubernetes
    helm template root-app/ | kubectl apply -f -