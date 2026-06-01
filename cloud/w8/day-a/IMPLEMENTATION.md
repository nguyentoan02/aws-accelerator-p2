# Implementation Guide

## Structure

```text
cloud/
  w8/
    day-a/
      README.md
      STUDY_PLAN.md
      IMPLEMENTATION.md
      EVIDENCE.md
      terraform/
        main.tf
        variables.tf
        outputs.tf
        terraform.tfvars.example
```

## Practice Exercise

The goal of this exercise is to practice Terraform on a realistic AWS setup: provisioning an EC2 instance inside a custom VPC with a complete minimum public networking path.

### What the Terraform Sample Does
- Creates a custom VPC.
- Creates one public subnet in a selected availability zone.
- Attaches an internet gateway and configures a public route table.
- Creates a security group with SSH and HTTP ingress rules.
- Launches one EC2 instance in the public subnet.
- Exposes key outputs such as VPC ID, subnet ID, security group ID, instance ID, public IP, and public DNS.

### Commands to Run

```powershell
cd D:\W8\W8\cloud\w8\day-a\terraform
Copy-Item .\terraform.tfvars.example .\terraform.tfvars
# Edit terraform.tfvars before running:
# - ami_id
# - key_name
# - ssh_allowed_cidrs
terraform init
terraform fmt
terraform validate
terraform plan -out tfplan
terraform apply tfplan
terraform output
terraform destroy
```

## Talking Points for Mentor Review

- Why the sample uses a custom VPC instead of the default VPC.
- Why a public subnet needs both an internet gateway and a route table.
- Why SSH CIDRs should be restricted instead of left open.
- The difference between `plan` and `apply`.
- What Terraform state stores and why it matters.
- Why `fmt` and `validate` should happen before `apply`.
