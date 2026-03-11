# YAML Examples for DevOps

A curated collection of practical YAML examples for DevOps engineers — covering CI/CD pipelines, Docker, Kubernetes, GitHub Actions, and Ansible.

## Repository Structure

```
yaml-examples-for-devops/
│
├─ README.md
├─ .gitignore
│
├─ ci-cd-pipelines/          # Azure DevOps pipeline definitions
│   ├─ dotnet-build.yml
│   ├─ nodejs-build.yml
│   └─ python-build.yml
│
├─ docker/                   # Docker Compose configurations
│   ├─ docker-compose-web.yml
│   ├─ docker-compose-db.yml
│   └─ docker-compose-full.yml
│
├─ kubernetes/               # Kubernetes manifests
│   ├─ deployment.yml
│   ├─ service.yml
│   └─ configmap.yml
│
├─ github-actions/           # GitHub Actions workflows
│   ├─ build-and-test.yml
│   ├─ deploy-to-azure.yml
│   └─ pull-request-check.yml
│
├─ ansible/                  # Ansible playbooks and inventory
│   ├─ playbook-install-nginx.yml
│   ├─ playbook-deploy-app.yml
│   └─ inventory.yml
│
└─ examples/                 # Basic YAML syntax examples
    ├─ simple-key-value.yml
    ├─ list-example.yml
    ├─ nested-objects.yml
    └─ comments-example.yml
```

## Categories

| Folder | Description |
|---|---|
| `ci-cd-pipelines/` | Azure DevOps `azure-pipelines.yml` patterns for .NET, Node.js, Python |
| `docker/` | `docker-compose` files for web apps, databases, and full stacks |
| `kubernetes/` | K8s Deployment, Service, and ConfigMap manifests |
| `github-actions/` | GitHub Actions workflows for CI, CD, and PR validation |
| `ansible/` | Ansible playbooks for server provisioning and app deployment |
| `examples/` | Beginner-friendly YAML syntax walkthroughs |

## Prerequisites

- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/)

## Author

**Said WAHID** — DevOps Engineer

---
*Licensed under MIT*
