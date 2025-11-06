# terraform-aws-s3-bucket

A simple Terraform module to create an AWS S3 bucket.
Update README: tag 1.1.0

## Usage

```hcl
module "s3_bucket" {
  source      = "policy-as-code-training/s3-bucket-ccr-1/aws"
  bucket_name = "my-bucket"
}
``` 