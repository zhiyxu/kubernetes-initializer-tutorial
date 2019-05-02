# Kubernetes Initializer Tutorial

This tutorial walks you through building and deploying a [Kubernetes Initializer](https://kubernetes.io/docs/admin/extensible-admission-controllers/#what-are-initializers) that injects an [Envoy](https://lyft.github.io/envoy) proxy container into uninitialized Deployments. 

> Initializers are an alpha feature and subject to change. Please report any Initializer specific issues on the [Kubernetes issue tracker](https://github.com/kubernetes/kubernetes/issues).

## Prerequisites

Kubernetes 1.7.0+ is required with [support for Initializers enabled](https://kubernetes.io/docs/admin/extensible-admission-controllers/#enable-initializers-alpha-feature). 

Please make sure you already have Kubernetes cluster running.

Download the tutorial by cloning this repository:

```
git clone https://github.com/zhiyxu/kubernetes-initializer-tutorial.git
```

```
cd kubernetes-initializer-tutorial
```

## Tutorial

* [Deploy The Envoy Initializer](Deployment/docs/deploy-envoy-initializer.md)
* [Initializing Deployments](Deployment/docs/initializing-deployments.md)
* [Initializing Deployments Based On Metadata](Deployment/docs/initializing-deployments-based-on-metadata.md)
* [Cleaning Up](Deployment/docs/cleanup.md)
* [Best Practices](Deployment/docs/best-practices.md)
