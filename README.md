# Jenkins_setup on k8s 

## For setting up a Jenkins cluster on Kubernetes, we will do the following.
1.	Create a Namespace
2.	Create a service account with Kubernetes admin permissions.
3.	Create local persistent volume for persistent Jenkins data on Pod restarts.
4.	Create a deployment YAML and deploy it.
5.	Create a service YAML and deploy it.
6.	Access the Jenkins application on a Node Port.


# Using Kustomize with Kubectl :
kustomize build Jenkins_setup


kustomize build Jenkins_setup | kubectl apply -f -