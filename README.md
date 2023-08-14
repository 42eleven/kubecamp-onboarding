# kubecamp-onboarding
An onboarding guide to make your KubeCamp session even smoother!

## Welcome!

If you are reading this, it means you have enrolled and will participate to an upcoming KubeCamp session! 

This short onboarding guide aspires to help you set up your personal computer/laptop in a way to make it more convenient to participate in the bootcamp's hands-on excersices as well as continue your Kubernetes journey! 

## What to expect

KubeCamp differs from other training sessions as we are striving to provide a collaborative, hands-on learning experience!

You can expect:

* a presentation in the background of instructors-led sessions to maintain the flow of our discussions
* practical examples to be provided and designed in a way to extend them and experiment either during the bootcamp or later on
* run the examples and discuss real-world scenarios on the spot
* open-ended discussions with the instructors and the other participants
* no video-like presentations where someone talks for ages
* no examples to follow on your own without guidance

## System prerequisites

There are a few components and tools it would be great to have installed and configured on your system, prior to joining the session on-site. This will help us all gain valuable time to spend in actual learning! 

But fear not! We have gathered all of the information you might need in this doc so that you don't have to stress!

1. `docker`: Docker will help us run and manage containers, hence it is an absolute must to install before continuing. Follow the official [installation instructions](https://docs.docker.com/get-docker/) according to your system.
2. `kind`: or `kubernetes-in-docker`. This will help us spawn Kubernetes clusters on our local machines during the bootcamp and run various examples. You can find the installation instructions [here](https://kind.sigs.k8s.io/docs/user/quick-start#installation).
3. `kubectl`: this is the kubernetes management cli tool. 
    * [Install kubectl on Linux](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux)
    * [Install kubectl on macOS](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos)
    * [Install kubectl on Windows](https://kubernetes.io/docs/tasks/tools/install-kubectl-windows)
4. `stern`: this tool lets you tail logs from multiple k8s pods with ease! We will explore this more during the bootcamp, but all you need to care at the moment is to follow the [installation instructions](https://github.com/stern/stern#installation)!
5. `kubectx + kubens`: tools to help you quickly change between k8s contexts and namespaces. [Installation instructions](https://github.com/ahmetb/kubectx#installation).
6. `k9s`: cli that a lot of people find more convenient to use in order to manage k8s clusters. You can find the installation instructions [here](https://k9scli.io/topics/install/).
7. `helm`: the package manager for Kubernetes! Please follow the installation [instructions](https://helm.sh/docs/intro/install/).
8. `kustomize` is a template-free way to customize application configuration. Optionally install it by following [these](https://kubectl.docs.kubernetes.io/installation/kustomize/) instructions.

We might need to install more tools during the bootcamp, but if you have this set already installed it will be an amazing start! 
