# ftp - AWS EC2-VPC Security Group Terraform module

## Usage

```hcl
module "ftp_security_group" {
  source = "terraform-aws-modules/security-group/aws//modules/ftp"

  # omitted...
}
```

All automatic values **ftp module** is using are available [here](https://github.com/terraform-aws-modules/terraform-aws-security-group/blob/master/modules/ftp/auto_values.tf).
