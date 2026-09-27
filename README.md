# ☁️ AWS VPC Terraform Modules

An enterprise-grade, highly customizable Terraform module designed to provision a secure, multi-AZ Virtual Private Cloud (VPC) architecture on AWS.

## 🏗️ Architecture Layout
* **Custom VPC:** Configured with robust DNS support and hostnames (`10.0.0.0/16`).
* **Public & Private Subnets:** Automatically provisions segmented subnets across multiple Availability Zones (AZs) for high availability.
* **Internet Gateway:** Connects public subnets securely to the outside world via customized Route Tables.
* **Infrastructure as Code (IaC):** Fully parameterized with inputs and structured outputs for seamless integration into larger cloud environments.

## 🛠️ Tech Stack
* **Cloud Provider:** Amazon Web Services (AWS)
* **Orchestration:** Terraform (HCL)

## 📦 Usage Guide

### 1. Clone the Repository
```bash
git clone [https://github.com/chaituupasi3-wq/aws-vpc-terraform-modules.git](https://github.com/chaituupasi3-wq/aws-vpc-terraform-modules.git)
cd aws-vpc-terraform-modules