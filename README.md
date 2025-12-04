# 🐍 AWS Python Samples

Code samples and best practices for AWS services using Python (boto3).

## Overview

This repository contains practical examples of AWS service integrations using Python, designed to be cataloged in Backstage Beach portal.

## Structure

```
aws-python-samples/
├── s3/                 # Amazon S3 examples
├── dynamodb/           # DynamoDB examples
├── lambda/             # Lambda function examples
├── ec2/                # EC2 automation
├── rds/                # RDS management
├── cloudformation/     # IaC templates
└── utils/              # Shared utilities
```

## Coming Soon

- **S3 Operations** - Upload, download, lifecycle management
- **DynamoDB CRUD** - Table operations and queries
- **Lambda Functions** - Serverless examples
- **EC2 Automation** - Instance management scripts
- **RDS Management** - Database provisioning and backup
- **CloudFormation** - Infrastructure as Code templates

## Prerequisites

```bash
# Python 3.9+
python --version

# AWS CLI configured
aws configure

# Install dependencies
pip install -r requirements.txt
```

## Usage

Each directory contains:
- `README.md` - Specific documentation
- `example.py` - Code sample
- `requirements.txt` - Dependencies
- `catalog-info.yaml` - Backstage catalog metadata

## Contributing

See [CONTRIBUTING.md](https://github.com/backstage-beach/.github/blob/main/CONTRIBUTING.md)

## License

Apache 2.0
