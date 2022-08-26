# Helm-chart-online-shopping-website

## To install Helmchart 
## Prerequisites
    Kubernetes 1.16+
    Helm 3+

## install helm using package manager
      snap install helm --classic

## To see the lsit of helm repo commands:
  https://helm.sh/docs/helm/helm_repo/

## To install helmfile command follow the below steps 
      1.wget -O helmfile_linux_amd64 https://github.com/roboll/helmfile/releases/download/v0.144.0/helmfile_linux_amd64
      2.chmod +x helmfile_linux_amd64
      3.mv helmfile_linux_amd64 /snap/helm/helmfile



### To RUN the Helm file
        helmfile sync
        
### To get the list 
        helmfile list
        
### to destroy the deployments and services created by helm file  
        helmfile destroy



