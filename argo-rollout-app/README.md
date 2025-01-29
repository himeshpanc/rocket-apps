# Argo Rollouts App

This directory contains the configuration for Blue-Green deployments using Argo Rollouts managed by ArgoCD.

## Structure
- `apps/` - Contains the application manifests
  - `base/` - Base Kubernetes manifests
  - `overlays/` - Environment specific overlays
- `charts/` - Contains Helm charts and values
- `rollout/` - Contains Argo Rollout specific configurations
