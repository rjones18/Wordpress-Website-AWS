# Wordpress-Website-AWS

In this project I created a Wordpress blog website in AWS using Terraform, Packer, and Ansible. Terraform was used to create the infrastructure while Packer used Ansible playbooks to install packages on a EC2 instance and create a AMI. The users post are being stored in a RDS MySQL database. I have also added a custom domain name through Route 53 and attached a SSL certificate for HTTPS via Certificate Manager.

## Application Breakdown

The application is broken down into the architecture below:

![wordpress](https://github.com/rjones18/Images/blob/main/wordpress)



Links to the other Repos for this Project:

- [Packer AMI Build](https://github.com/rjones18/Wordpress-AMI-Build)

- [Infrastructure](https://github.com/rjones18/Application-Infrastructure-)

- [Database](https://github.com/rjones18/RDS_Database)

- [VPC](https://github.com/rjones18/vpc-terraform-project)
