# 🚀 Headlamp Deployment using GitHub Actions & ArgoCD App of Apps (GitOps)
This repository demonstrates a GitOps-based deployment of the Kubernetes UI Headlamp using Helm, GitHub Actions, and Argo CD.
The goal of this project is to implement a production-style GitOps workflow where:
Helm charts are validated through CI
ArgoCD continuously syncs applications from Git
Kubernetes deployments are fully automated
This setup demonstrates how to deploy Headlamp using the ArgoCD App of Apps pattern.

# 📖 Medium Article
##A detailed step-by-step explanation is available in the Medium article:
##👉 Read the full guide: https://medium.com/@rahulbnp52/deploy-headlamp-using-github-actions-and-argocd-app-of-apps-pattern

# 🏗 Architecture
The following architecture shows the CI + GitOps workflow.
'''Developer
   │
   ▼
GitHub Repository
   │
   ▼
GitHub Actions
(Helm Lint + Validation)
   │
   ▼
GitOps Repository
   │
   ▼
ArgoCD App of Apps
   │
   ▼
Helm Chart Deployment
   │
   ▼
Headlamp running in Kubernetes'''
