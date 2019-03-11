# ARM Templates for Deploying Rancher a Multi-Cluster Kubernetes Operations and Workload Management solution to Azure
This repository consists of ARM templates for deploying Rancher (https://www.rancher.com) and a host VM for Kubernetes to Azure. This is intended for labs to learn Rancher. Not intended for use in production. 

ARM Template #1 named RancherNode.JSON will deploy an Ubuntu VM with Docker and the latest version of Rancher (https://hub.docker.com/r/rancher/rancher) from Docker Hub. ARM Template #2 named RancherHost.JSON will deploy an Ubuntu VM with Docker to be used as a Kubernetes host in Rancher. 


<a href="https://azuredeploy.net/?repository=https://github.com/Buchatech/DeployRanchertoAzure" target="_blank">
    <img src="https://azuredeploy.net/deploybutton.png"/>
</a>

For more information overall and for the steps on adding the VM as a host to Rancher visit this blog post:
