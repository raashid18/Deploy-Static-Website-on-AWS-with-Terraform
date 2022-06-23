# Deploy-Static-Website-on-AWS-with-Terraform

![terraform](https://user-images.githubusercontent.com/67089791/175224641-e5bc40ee-7f53-4f5a-a582-bf2e92b3dccf.jpeg)


# Terraform

Terraform is an infrastructure as code tool that lets you define both cloud and on-prem resources in human-readable configuration files that you can version, reuse, and share. You can then use a consistent workflow to provision and manage all of your infrastructure throughout its lifecycle. Terraform can manage low-level components like compute, storage, and networking resources, as well as high-level components like DNS entries and SaaS features.

# AWS

Amazon Web Services (AWS) is the world’s most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally. Millions of customers including the fastest growing startups, largest enterprises, and leading government agencies are using AWS to lower costs, become more agile, and innovate faster.




# Steps to create the Infrastructure

Step1:- Setup VS Code enviroment for terraform.

Step2:- configured aws provider with proper credentials.

Step3:- create default vpc if one does not exit.

Step4:- use data source to get all avalablility zones in region.

Step5:- create default subnet if one does not exit.

Step6:- create security group for the ec2 instance.

Step7:- use data source to get a registered amazon linux 2 ami.

Step8:- launch the ec2 instance and install website.

Step9:- print the ec2's public ipv4 address.
