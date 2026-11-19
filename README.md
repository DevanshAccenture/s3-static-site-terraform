# Static Website on S3 using Terraform

![Terraform CI](https://github.com/DevanshAccenture/s3-static-site-terraform/actions/workflows/terraform-ci.yml/badge.svg)

Creates an S3 bucket with static website hosting, uploads index.html and makes the site publicly readable. The CI pipeline runs `terraform fmt`, `init` and `validate` on every push.
