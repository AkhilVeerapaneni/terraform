# terraform
# installation of terraform code
# Install dependencies
sudo yum install -y yum-utils curl unzip gnupg

# Add HashiCorp repository
sudo yum-config-manager --add-repo https://rpm.releases.hashicorp.com/AmazonLinux/hashicorp.repo

#n Install Terraform
sudo yum install -y terraform

# Verify installation
terraform -versio
