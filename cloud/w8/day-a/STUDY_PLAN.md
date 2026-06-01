# Study Plan

## 1. Scope for Today

Based on the Phase 2 announcement, the focus for `Monday, 2026-06-01` is:
- IaC overview
- HCL syntax
- Terraform workflow basics: `init`, `plan`, `apply`, `destroy`

## 2. Core Topics to Understand

### IaC Overview
- Infrastructure is defined as code instead of being created manually.
- Infrastructure code supports version control, peer review, reuse, and automation.
- Terraform uses a declarative model: we define the desired state, and Terraform calculates how to reach it.

### HCL Syntax
- Terraform is organized into named blocks such as `terraform`, `provider`, `resource`, `variable`, and `output`.
- Attributes use the format `key = value`.
- `locals` can be used to centralize small pieces of logic and reduce duplication.
- Input variables and outputs improve reuse and clarity.

### Workflow Basics
1. `terraform init`
2. `terraform fmt`
3. `terraform validate`
4. `terraform plan`
5. `terraform apply`
6. `terraform destroy`

## 3. Deliverables for Mentor Review

- A clear README describing the learning scope and objectives.
- A small Terraform sample that provisions AWS infrastructure with standard networking components.
- A command log and expected outputs.
- A short checklist and reflection section.
