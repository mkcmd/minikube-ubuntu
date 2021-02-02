# minikube-ubuntu
Cancer free local kubernetes development 

## Getting started

Assuming you have vagrant installed:

```vagrant up && vagrant ssh```

`kubectl get all` will show you the empty cluster, note that if you want to
test locally built docker images you'll need to build them in the vagrant
box.
