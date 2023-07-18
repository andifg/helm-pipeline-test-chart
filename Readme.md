# Helm Pipeline Test Chart

## Description

This repository is part of two repositories to experiment with Tekton pipelines
as code and argocd gitops deployment:
- [Helm Chart Repository]()
- [GitOps Application referencing Helm Chart]()


## Local Testing

- Enable CLI access to registry

### Example with AWS ECR

```bash
aws ecr-public create-repository --repository-name helm-charts
```
