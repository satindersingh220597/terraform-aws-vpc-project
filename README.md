# 🚀 Terraform AWS Infrastructure Project

## 📌 Project Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision AWS infrastructure including:

- VPC
- Public Subnet
- Internet Gateway
- Route Table
- Security Group
- EC2 Instance

The infrastructure enables a publicly accessible EC2 instance using proper AWS networking configuration.

---

## 🏗 Architecture Diagram

(Insert diagram image here)

---

## 🧱 Architecture Components

### 🔹 VPC
- CIDR: 10.0.0.0/16
- Isolated network environment

### 🔹 Public Subnet
- CIDR: 10.0.1.0/24
- Auto-assign public IP enabled

### 🔹 Internet Gateway
- Enables internet connectivity

### 🔹 Route Table
- Default route (0.0.0.0/0) to Internet Gateway

### 🔹 Security Group
- Allows:
  - SSH (22)
  - HTTP (80)

### 🔹 EC2 Instance
- Amazon Linux 2
- Dynamic AMI lookup using Terraform data source

---

## 📂 Project Structure

