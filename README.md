# 🚀 Day 19 – Terraform & Infrastructure as Code (IaC)

---

# 📌 Overview

On Day 19, I explored Terraform and Infrastructure as Code (IaC), which help automate cloud infrastructure deployment using configuration files.

This day focused on:

* Infrastructure as Code
* Terraform basics
* Providers & Resources
* Terraform workflow
* State management
* AWS infrastructure automation

---

# ☁️ What is Infrastructure as Code (IaC)?

Infrastructure as Code allows developers to create and manage infrastructure using code instead of manual configuration.

Benefits:

* Automation
* Faster deployments
* Version control
* Consistency
* Scalability

---

# 🔑 What is Terraform?

Terraform is an open-source IaC tool developed by HashiCorp.

It helps:

* Automate infrastructure
* Provision cloud resources
* Manage multi-cloud environments
* Deploy repeatable architectures

---

# 🧱 Terraform Core Components

## 1. Provider

Connects Terraform with cloud platforms.

### Example:

* AWS
* Azure
* Google Cloud

---

## 2. Resource

Defines infrastructure components.

### Examples:

* EC2 instance
* S3 bucket
* VPC

---

## 3. State File

Tracks infrastructure changes.

---

## 4. Variables

Reusable configuration values.

---

## 5. Modules

Reusable infrastructure templates.

---

# ⚙️ Terraform Workflow

```plaintext id="7x5f3n"
Write Terraform Code
        ↓
terraform init
        ↓
terraform plan
        ↓
terraform apply
        ↓
AWS Resources Created
```

---

# 🌐 Real-World Project – Automated AWS Infrastructure

---

# 🏗️ Project Objective

Build automated AWS infrastructure where:

* Terraform creates VPC
* EC2 instances launch automatically
* Security Groups configured
* S3 bucket created
* Infrastructure managed as code

---

# 🧠 Project Architecture

```plaintext id="g8p2zw"
Terraform Code
      ↓
AWS Provider
      ↓
VPC + EC2 + S3
      ↓
Cloud Infrastructure
```

---

# 🔐 Security Features

* IAM permissions
* Secure Terraform state
* Least privilege access
* Version-controlled infrastructure

---

# 📊 Monitoring & State Management

## Terraform State File

Tracks:

* Resource creation
* Updates
* Infrastructure changes

---

## CloudWatch Monitoring

Tracks:

* EC2 health
* Infrastructure metrics
* Resource utilization

---

# 💻 Example Terraform Code

## Create EC2 Instance

```hcl id="r2v8mk"
provider "aws" {
  region = "ap-south-1"
}

resource "aws_instance" "web" {
  ami           = "ami-123456"
  instance_type = "t2.micro"
}
```

---

# 🔟 Real-World Use Cases

1. Automated cloud deployment
2. Multi-cloud infrastructure
3. DevOps automation
4. Kubernetes infrastructure
5. CI/CD pipelines
6. Enterprise cloud provisioning
7. AI/ML infrastructure setup
8. Disaster recovery environments
9. Secure networking deployment
10. Scalable cloud platforms

---

# 🧪 Hands-On Tasks

## Task 1

Install Terraform.

---

## Task 2

Configure AWS provider.

---

## Task 3

Create EC2 instance using Terraform.

---

## Task 4

Run terraform init & apply.

---

## Task 5

Destroy infrastructure safely.

---

# 🧠 What I Learned

* Infrastructure as Code concepts
* Terraform workflow
* AWS automation
* State management
* Cloud infrastructure provisioning

---

# 🚀 Next Step (Day 20)

* CI/CD Pipelines with GitHub Actions & AWS

---

# 📌 Author

**Sankar S**
Cloud & AI Learning Journey 🚀
