# IAM Policy Autopilot with EKS and ALB

This repository tests how to use **AWS IAM Policy Autopilot** to generate
least-privilege IAM policies for a real-world Kubernetes workload running on **Amazon EKS**
and exposed via an **AWS Application Load Balancer (ALB)**.

## Why this project?

This project explores whether **IAM Policy Autopilot** can:

- Reduce policy size
- Improve least-privilege
- Make IAM policies easier to understand and maintain

- ## What this project builds

- An Amazon EKS cluster
- A simple containerised "hello-world" application
- AWS Load Balancer Controller using IRSA
- An Application Load Balancer created by Kubernetes Ingress
- IAM policies generated using IAM Policy Autopilot

- Infrastructure and deployments are applied using **GitHub Actions** with AWS OIDC
  authentication

## Prerequisites

Before getting started, I had to install following tools on my Windows machine:

- Docker Desktop - https://docs.docker.com/desktop/setup/install/windows-install/
- Ubuntu WSL - https://ubuntu.com/desktop/wsl
- AWS CLI - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
- Kubectl - https://kubernetes.io/docs/tasks/tools/install-kubectl-windows/
- Ekstl - https://docs.aws.amazon.com/eks/latest/eksctl/installation.html

## Instructions on how to use IAM policy Autopilot locally

- https://github.com/awslabs/iam-policy-autopilot
- https://aws.amazon.com/about-aws/whats-new/2025/11/iam-policy-autopilot-generate-iam-policies-code/
