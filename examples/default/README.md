# ECDSA Certificate Authority with private CRL (default)

## Local Development - Terraform
* You need to have docker installed
* from within this subdirectory:
```
terraform init -backend-config=bucket={YOUR_TERRAFORM_STATE_BUCKET} -backend-config=key=terraform-aws-ca -backend-config=region={YOUR_TERRAFORM_STATE_REGION}
terraform plan
terraform apply
```

## Local Development - Python
see [Lambda Submodule README](../../modules/terraform-aws-ca-lambda/README.MD)
