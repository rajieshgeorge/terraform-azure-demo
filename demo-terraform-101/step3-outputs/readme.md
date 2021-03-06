# Using variables
Expose created resources.

## Resources
- Documentation:
  - Terraform >= 0.12: https://www.terraform.io/docs/configuration/outputs.html
  - Terraform <= 0.11: https://www.terraform.io/docs/configuration-0-11/outputs.html
- Tutorial: https://learn.hashicorp.com/terraform/azure/outputs_az

## Goal
Understand :
- usage of output

## Setup
If not done already, login to Azure:
```bash
az login
```

Initialize your workspace once:
```bash
# Init cloud provider plugin & template plugin
terraform init
```

## Usage
Apply deployment (ouputs will be displayed once completed):
```bash
terraform apply
```

You can also display outputs values after deployment, using the Terraform state:
```bash
terraform output
```

## Teardown
Destroy resources when finished:
```bash
terraform destroy
```
