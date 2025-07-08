# Apigee Integration: Control Plane Automation

Automate the provisioning and configuration of **Apigee X or Hybrid** resources via the control plane. This repo provides a CLI-driven and optionally declarative approach to managing proxies, environments, target servers, KVMs, API products, and more.

---

## 🔧 Features

- Provision API Proxies, Target Servers, and Key-Value Maps (KVMs)
- Create and manage Environments, EnvGroups, and API Products
- Declarative integration options (YAML)
- Support for Apigee X and Hybrid control plane
- Cloud-native and CI/CD ready

---

## ⚙️ Requirements

- GCP Project with Apigee enabled  
- IAM role: `roles/apigee.admin` or equivalent  
- [Google Cloud SDK](https://cloud.google.com/sdk/docs/install)  
- [apigeecli](https://github.com/apigee/apigeecli) installed  
- (Optional) Terraform or Cloud Build for infra automation

---

## 🚀 Quick Start

### 1. Clone the Repo

```bash
git clone https://github.com/YOUR_ORG/apigee-integration.git
cd apigee-integration
