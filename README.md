# Terraform

Create VPC in aws using terraform

Within the directory that the two files are located issue:
terraform init
The init argument will initialize the environment.
Then issue:
terraform plan -out vpc.plan
The plan argument will syntax check the files and prepare the deployment.
Deploy the VPC:
terraform apply vpc.plan
This will deploy the AWS VPC. To view data about the VPC/Subnet/Security Group from your local Linux box execute:
terraform show
