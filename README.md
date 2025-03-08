# Instructions

#### Packer
Make sure you have a default vpc, and can access your AWS account by either using environmental variables or stored aws credentials
Do the following command in the parent folder\
`packer init packer/`\
`packer build packer/`\
If encounter "Gathering Facts" error, in the provisioner block add `use_proxy=false`

#### Terraform
Go to the terraform directory
`terraform init`\
`terraform validate`\
`terraform plan`\
`terraform apply`

If you go to the IPv4 address of your EC2 instance that appears at the end, you will see this page, which means everything worked successfully.

![image](https://github.com/user-attachments/assets/d20ebfc0-78b5-42a5-941d-cecb0f7845fd)

