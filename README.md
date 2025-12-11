# Trusted AI App

This repository contains the Trusted AI Application for the Red Hat Trusted Supply Chain demo.

## Structure

- `k8s/` - Kubernetes manifests for deployment
- `phase2-build/app-source/` - Application source code and build artifacts

## ArgoCD Applications

This repository is used by ArgoCD for GitOps deployments:
- Staging: `trusted-ai-staging`
- Production: `trusted-ai-production`
