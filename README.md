# fem-eci-terraform-aws-network
Automation for AWS Network Settings

All pulled from Erik Reinhart's 
https://github.com/ALT-F4-LLC/fem-eci-terraform-aws-network/tree/05-setup-aws-automation

Which includes many existing hashicorp and aws modules

## main.tf
  ### hashicorp subnet module
    computational handling of every possible subnet

## variables.tf
  allows us to manipulate network stuff later on, externally configurable network stuff

# running
only need to 
terraform init 
terraform validate