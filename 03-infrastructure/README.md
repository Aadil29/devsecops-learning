# Infrastructure as Code

Write Terraform, scan it, fix it.

## What to build

- Terraform config provisioning a VPC, storage bucket, and security group (AWS, or LocalStack if no cloud access)
- Add `tfsec` or `checkov` to CI — run on every push
- Intentionally misconfigure something (public S3 bucket, open security group) then fix it

## Done when

- [ ] Terraform defines at least 3 resources
- [ ] tfsec/checkov runs in CI and catches the misconfiguration
- [ ] Misconfiguration fixed, scan passes
- [ ] Notes written up

## Notes

See [notes/](notes/)

## Project repos

_None yet._
