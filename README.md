
- ## What this project builds

- An Amazon EKS cluster
- A simple containerised "hello-world" application
- AWS Load Balancer Controller using IRSA
- An Application Load Balancer created by Kubernetes Ingress

- Infrastructure and deployments are applied using **GitHub Actions** with AWS OIDC
  authentication

## Prerequisites

Before getting started, I had to install the following tools on my Windows machine:

- Docker Desktop - https://docs.docker.com/desktop/setup/install/windows-install/
- Ubuntu WSL - https://ubuntu.com/desktop/wsl
- AWS CLI - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
- Kubectl - https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/
- Ekstl - https://docs.aws.amazon.com/eks/latest/eksctl/installation.html
