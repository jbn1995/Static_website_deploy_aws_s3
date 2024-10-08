# Static_website_deploy_aws_s3# AWS S3 Static Website Deployment using Terraform

This repository contains Terraform code to create an S3 bucket in AWS and deploy a static website. Additionally, it includes a deployment script for automating the process of uploading the website files to the S3 bucket.

## Project Overview

This project automates the following:

1. **Creation of an S3 bucket** in AWS.
2. **Hosting a static website** using S3.
3. **Deployment script** to upload website files to the S3 bucket.

## Features

- Automatically provisions an S3 bucket.
- Configures the bucket to serve static website content.
- Automates deployment of static files (HTML, CSS, JS) to the S3 bucket.
- Supports public access for static website hosting.

## Files

- `main.tf`: Terraform configuration file to create the S3 bucket.
- `variables.tf`: Defines input variables for customization (e.g., bucket name).
- `outputs.tf`: Specifies outputs like the S3 bucket URL.
- `provider.tf`: Providers information and region where s3 bucket will be created.

## Prerequisites

Before using this project, make sure you have:

- [Terraform](https://www.terraform.io/downloads.html) installed.
- An AWS account with the appropriate permissions to create S3 buckets.
- AWS CLI configured with credentials.
  

