# OpenChoreo GitOps

This repository contains a sample GitOps setup for OpenChoreo.

## Cluster Setup with Flux

1. Install [Flux CLI](https://fluxcd.io/flux/installation/#install-the-flux-cli).
2. Run `flux install` to install Flux controllers and CRDs in the cluster.
3. Run `kubectl apply -f flux-conf.yaml` set up the GitOps repository sync.
