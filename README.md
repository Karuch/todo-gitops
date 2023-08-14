**Gitops** 

**Description**
This repository contains the following charts:
todo app chart
efk stack chart (elastic, fluentd, kibana)
kube-prometheus-stack chart (prometheus, grafana)

ArgoCD monitors this repo, deploys all the charts here and change the state of the cluster to match the content of the charts. 

**Installation**
git clone https://gitlab.com/tal_docs/portfolio-docker.git|
helm install tal-todo -n todo todo --create-namespace
helm install kube-prometheus-stack -n metrics metrics --create-namespace
helm install efk-stack -n efk efk --create-namespace

**Support**
talk474747@gmail.com

**Contributing**
Not intersting in contributing currently.

**Authors and acknowledgment**
Written by Tal.

**Project status**
Completed.