# DevOps Final Project - GitOps Repository

This repository contains the GitOps configuration for the Flask AWS Monitor application.

ArgoCD uses this repository to deploy the application into multiple Kubernetes environments using an ApplicationSet.

## Repository Structure

```text
devops-final-gitops/
├── applicationsets/
│   └── flask-applicationset.yaml
└── flask-aws-monitor/
    ├── dev/
    │   └── values.yaml
    ├── qa/
    │   └── values.yaml
    └── prd/
        └── values.yaml