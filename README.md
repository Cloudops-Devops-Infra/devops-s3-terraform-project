# DevOps S3 Terraform Project

## Project Overview

This project demonstrates AWS S3 operations using AWS CLI, Terraform, Docker, and Floci (local AWS emulator).

The objective was to learn cloud storage management and Infrastructure as Code (IaC) concepts commonly used in DevOps environments.

## Technologies Used

* AWS CLI
* Terraform
* Docker
* Git
* GitHub
* Floci

## Features Implemented

* Created multiple S3 buckets
* Uploaded files to S3
* Downloaded files from S3
* Uploaded folders recursively
* Synced local folders with S3 using aws s3 sync
* Created S3 buckets using Terraform
* Managed infrastructure as code

## Commands Practiced

```bash
aws s3 mb
aws s3 ls
aws s3 cp
aws s3 sync
terraform init
terraform plan
terraform apply
```

## Project Structure

```text
devops-s3-terraform-project
│
├── terraform-s3
│   ├── main.tf
│   └── .terraform.lock.hcl
│
├── website
│   ├── index.html
│   └── about.html
│
├── backup
│   ├── index.html
│   └── about.html
│
└── screenshots
```

## Learning Outcomes

* AWS S3 fundamentals
* Infrastructure as Code with Terraform
* Git and GitHub workflows
* Local cloud emulation using Docker and Floci
* DevOps automation concepts
