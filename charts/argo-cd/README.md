# install argo-cd using helm:
    https://www.arthurkoziel.com/setting-up-argocd-with-helm/
    
    # create a charts folder:
        mkdir -p charts/argo-cd
    # add the helm repo for argo-cd:
        helm repo add argo-cd https://argoproj.github.io/argo-helm
        helm dep update charts/argo-cd -- creates a chart.lock with the right version
    # helm install from the chart
        helm install argo-cd charts/argo-cd

    