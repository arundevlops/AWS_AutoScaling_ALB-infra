This is an Terraform script which will deploys a AWS Autoscaling Apllication Load balancer infrastructure


How to Run:

terraform init
terraform apply --auto-approve -var-file=tfvarfile.tfvars 
terraform destroy --auto-approve -var-file=tfvarfile.tfvars 