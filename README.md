# What is this?

This repo provides a means to publish a helm chart for https://github.com/cruise-automation/k-rail

Further details at https://medium.com/cruise/securing-kubernetes-with-k-rail-5f77a1a11174

## How do I use it?

1. Install the repo:

```
helm repo add funkypenguin-k-rail https://funkypenguin.github.io/helm-k-rail/
helm repo update
```

2. Install the chart:

```
helm install funkypenguin-k-rail/k-rail
```