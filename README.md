# AWS Nomad Terraform

AWS Nomad Terraform

## Requirements
- An AWS account
- Minimum of Terraform version 13 and have setup the `variables.tf` with your preferred configuration.

## How to run
Initialize providers
```
terraform init
```

Deploy infrastructure
```
terraform apply --auto-approve
```

Show infrastructure
```
terraform show
```

Show outputs
```
terraform output
```

Destroy infrastructure
```
terraform destroy --auto-approve
```