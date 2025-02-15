# skaffold-helm-tutorial

This tutorial gives you hands on docker, kubernetes, helm and skaffold experience. This is done using a very simple application: vue on the frontend and fastapi pyython on the backend. The only functionality is to get the time!

## How to work with this tutorial

You can set up a hetzner cloud environment if you don't want to work on a local machine. You can do this using the pulumi stack [here](remote-environment-setup).

As an alternative, you can work locally. Make sure you have a recent linux distribution with docker installed (eg ubuntu 20.04 with the docker.io package). In order to follow this tutorial in a comfortable way, adhere to:

* At least 8GB of ram (16 will be even more comfortable, especially if you want to run a heavy IDE)
* At least 40GB of disk space. When disk space is getting low, kubernetes taints your nodes and your pods won't run anymore!
* Don't use a hard disk, use a SSD or kubernetes will be horribly slow. Preferably a nvme ssd, not a SATA one.

If you decided to work remotely, you probably want to use [Visual studio code remote SSH extension](REMOTE.md)

## The tutorial: table of contents:

* Chapter 1: [Installing k3s](chapters/01-install-k3s.md)
* Chapter 2: [Dockerize our API](chapters/02-dockerize-backend.md)
* Chapter 3: [Dockerize our frontend app](chapters/03-dockerize-frontend.md)
* Chapter 4: [Kubernetes](chapters/04-kubernetes.md)
* Chapter 5: [Helm](chapters/05-helm.md)
* Chapter 6: [Skaffold](chapters/06-skaffold.md)
* Chapter 7: [A production version of our frontend container](chapters/07-frontend-production.md)
* Chapter 8: [Ingress](chapters/08-ingress.md)


