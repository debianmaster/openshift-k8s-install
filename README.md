# Openshift and (kubernetes) k8s install
Notes for Openshift Origin and k8s  installation

### Pre-requisites 
>  Install following based on your environment.


https://www.virtualbox.org/wiki/Downloads
https://www.vagrantup.com/downloads.html


### Install k8s (minikube)

#### Intall k8s command line (kubectl)
http://kubernetes.io/docs/getting-started-guides/minikube/#download-kubectl
```sh
curl -Lo kubectl http://storage.googleapis.com/kubernetes-release/release/v1.3.0/bin/darwin/amd64/kubectl && chmod +x kubectl && sudo mv kubectl /usr/local/bin/
```

#### Install minikube (server) 
> for Mac OSX 64

```sh
curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
```



