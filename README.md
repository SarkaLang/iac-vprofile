# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3

# Two branches
* main
* stage

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####
#####
