# ArgoCD Repository

This repository contains ArgoCD application definitions and configurations.

## Structure

- `apps/` - Application manifests organized by environment (dev, uat, prd)
- `argocd/` - ArgoCD application definitions organized by environment (dev, uat, prd)
- `releases/` - Auto-populated with release manifests for each new deployment

## Environments

- **dev** - Development environment
- **uat** - User Acceptance Testing environment
- **prd** - Production environment
