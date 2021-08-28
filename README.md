# Auto provisioning of AWS-EKS cluster

Terraform code to provision a simple EKS cluster on AWS. These scripts create:-

* A custom VPC using aws vpc module
* A managed EKS cluster with autoscaling group of worker nodes using aws eks module

NOTE: Modify the backend.tf to store state file remotely.
