# Evidence

## Checklist

- [ ] Read an IaC overview
- [ ] Understand the basic HCL structure
- [ ] Run `terraform init`
- [ ] Run `terraform fmt`
- [ ] Run `terraform validate`
- [ ] Run `terraform plan`
- [ ] Run `terraform apply`
- [ ] Verify the EC2 instance, VPC, subnet, and security group outputs
- [ ] Run `terraform destroy`

## Command Log

```powershell
cd D:\W8\W8\cloud\w8\day-a\terraform
Copy-Item .\terraform.tfvars.example .\terraform.tfvars
terraform init
terraform fmt
terraform validate
terraform plan -out tfplan
terraform apply tfplan
terraform output
terraform destroy
```

## Reflection

### What I Learned
- Terraform uses declarative syntax to define infrastructure.
- The `init -> plan -> apply -> destroy` workflow is the basic loop I need to master.
- State is critical because Terraform needs a source of truth for managed resources.
- Even a basic EC2 deployment depends on surrounding networking resources such as VPC, subnet, route table, internet gateway, and security group.

### Current Gaps
- I still need to select the correct AMI for the target region.
- I still need more practice reading `terraform plan` output confidently.
- I should keep reinforcing the difference between provider, resource, variable, and output roles.

### Questions for Mentor
1. When should a team start extracting Terraform modules instead of keeping everything in a single root module?
2. What naming, folder structure, and remote state conventions do you usually enforce in production teams?
3. In production, should `plan` review and `apply` approval happen locally or only through CI/CD?
