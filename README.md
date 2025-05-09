# AWS Infrastructure Templates 🚀

This repository contains a collection of reusable AWS CloudFormation templates and IAM policy documents.

## 📁 Contents

### 🟨 CloudFormation Templates (`cloudformation/`)
| Template Name         | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `vpc-basic.yaml`       | Creates a basic VPC with a public subnet and internet access                |

### 🟦 IAM Policies (`iam-policies/`)
| Policy Name                   | Description                                                          |
|------------------------------|----------------------------------------------------------------------|
| `s3-readonly-access.json`     | Grants read-only access to a specific S3 bucket                      |
| `lambda-execution-role.json`  | Grants basic execution permissions for Lambda functions              |

---

## ✅ Benefits of Using These Templates

### 📌 CloudFormation Templates
- **Infrastructure as Code (IaC):** Define, version, and automate infrastructure using YAML/JSON.
- **Repeatable Deployments:** Ensure consistent environments across dev, test, and prod.
- **Faster Setup:** Save time by avoiding manual setup of VPCs, EC2, S3, etc.
- **Rollback Support:** Quickly undo changes if something goes wrong.

### 📌 IAM Policies
- **Least Privilege Access:** Apply specific permissions instead of giving full access.
- **Reusable & Auditable:** Centralized management of permissions makes audits and debugging easier.
- **Modular:** Assign policies to multiple users, roles, or services as needed.

---

## 📥 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/XXXXXXXXXXX/XXXXXXXXXXXXXXXX.git
