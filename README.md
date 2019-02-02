# terraform-kubernetes-eks-workers

Applies the config map needed for worker nodes to connect to an EKS cluster

## Usage

```terraform
module "this" {
  source       = "github.com/jjno91/terraform-kubernetes-eks-workers?ref=master"
  iam_role_arn = "ARN of your EKS worker IAM role"
}
```
