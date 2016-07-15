# Openshift and (kubernetes) k8s install
Notes for Openshift Origin and k8s  installation

### Pre-requisites 
>  Install following based on your environment.
##### Install Virtual box
https://www.virtualbox.org/wiki/Downloads
##### Install Vagrant
https://www.vagrantup.com/downloads.html
##### Install Docker for Mac/Windows
https://docs.docker.com/engine/installation/mac/


##### For linux/centos
```sh
# tee /etc/yum.repos.d/docker.repo <<-'EOF'
[dockerrepo]
name=Docker Repository
baseurl=https://yum.dockerproject.org/repo/main/centos/7/
enabled=1
gpgcheck=1
gpgkey=https://yum.dockerproject.org/gpg
EOF

# yum install docker-engine
# systemctl start docker
```



### Install k8s (minikube)


##### Intall k8s command line (kubectl)
http://kubernetes.io/docs/getting-started-guides/minikube/#download-kubectl
> for Mac OSX 64

```sh
curl -Lo kubectl http://storage.googleapis.com/kubernetes-release/release/v1.3.0/bin/darwin/amd64/kubectl && chmod +x kubectl && sudo mv kubectl /usr/local/bin/
```
##### Install minikube (server) 
```sh
curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/
```


### Install openshift origin (via vagrant)
##### Install openshift cli 
> For MAC OSX





