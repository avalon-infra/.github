# Avalon

Hey there! Welcome to **Avalon**. This is my personal playground where I share the source code of my self-hosted applications and Kubernetes infrastructure. Here, you’ll find everything I’ve tinkered with in the realm of self-hosting.

---

## 🛠️ Infrastructure

At the core of Avalon is a powerful **Kubernetes** setup paired with **ArgoCD** for continuous delivery. This setup allows me to easily deploy, manage, and scale my applications, providing both resilience and flexibility.

### Key Features

- **ArgoCD Integration**: I use ArgoCD for GitOps-style continuous deployment, ensuring that my applications are managed directly from the source code repository.
- **Custom Deployments**: Each application is crafted with care, making sure it fits seamlessly into my ecosystem.
- **Simplified Management**: With Kubernetes and ArgoCD, managing resources and scaling applications is a breeze.
- **Learning by Doing**: This project is as much a learning tool for me as it is a functional environment.

### Architecture Overview

Here’s a simple representation of my setup:

![TODO Kubernetes Architecture](link-TODO)

---

## 📦 Services hosted on Kubernates

Here is a non exhaustive list of the services hosted on Avalon and their source code:

| Application        | Description                               | Repository Link                                        |
|--------------------|-------------------------------------------|--------------------------------------------------------|
| **Portfolio**      | Web portfolio served with nginx (static)  | [View Repo](https://github.com/avalon-infra/portfolio) |
| **Vaultwarden**    | Password vault compatible with bitwarden  | --                                                     |
| **Postgresql**     | Common database for all services          | --                                                     |
| **Vault**          | Secret vault to use accross services      | --                                                     |
| **Affine**         | All-in-one productivity suite             | --                                                     |
| **ArgoCD**         | GitOps-style continuous deployment        | --                                                     |
