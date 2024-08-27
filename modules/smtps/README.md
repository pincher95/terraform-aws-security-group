# smtps - AWS EC2-VPC Security Group Terraform module

## Usage

```hcl
module "smtps_security_group" {
  source  = "terraform-aws-modules/security-group/aws//modules/smtps"
  version = "~> 6.0"

  # omitted...
}
```

All automatic values **smtps module** is using are available [here](https://github.com/terraform-aws-modules/terraform-aws-security-group/blob/master/modules/smtps/auto_values.tf).

<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
