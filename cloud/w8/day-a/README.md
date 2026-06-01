# W8 Day A - Terraform Foundation

Study date: `2026-06-01`

## Learning Objectives

- Understand what Infrastructure as Code (IaC) is and why it matters.
- Learn the basic HCL syntax used in Terraform.
- Practice the core Terraform workflow: `init`, `plan`, `apply`, `destroy`.
- Build a small runnable Terraform sample as daily evidence.

## Documents

- [Study Plan](D:\W8\W8\cloud\w8\day-a\STUDY_PLAN.md)
- [Implementation Guide](D:\W8\W8\cloud\w8\day-a\IMPLEMENTATION.md)
- [Evidence](D:\W8\W8\cloud\w8\day-a\EVIDENCE.md)
- [Terraform sample](D:\W8\W8\cloud\w8\day-a\terraform)

## What Is Included

- A Terraform sample that creates an `EC2` instance inside a custom `VPC`.
- Supporting AWS networking resources: public subnet, internet gateway, route table, and route table association.
- A dedicated `security group` with inbound SSH and HTTP rules plus outbound internet access.
- Practical examples of `terraform`, `provider`, `variable`, `locals`, `resource`, and `output` blocks.

## Expected Outcome

- Run `terraform init` successfully.
- Review planned changes with `terraform plan`.
- Provision an EC2 instance in a custom VPC with `terraform apply`.
- Clean up the environment with `terraform destroy`.
