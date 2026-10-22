# Build an ETL Pipeline on EMR using AWS CDK and Power BI

The objective of this project is to build an ETL Pipeline on Amazon EMR through AWS CDK.

## Overview
Infrastructure as Code (IaC) is a practice of automating the provisioning and management of IT infrastructure using software engineering techniques. It involves creating and maintaining the infrastructure through code rather than manually configuring individual components.

IaC is typically used in cloud computing environments, where it enables developers and operations teams to automate the deployment and management of resources, such as servers, storage, and networking. It enables organizations to achieve more consistent, reliable, and scalable infrastructure that can be easily replicated across multiple environments.

IaC can be implemented using various tools and platforms, such as Terraform, AWS CloudFormation, Azure Resource Manager, and Google Cloud Deployment Manager. These tools enable the creation of infrastructure templates or scripts that define the desired configuration and state of the infrastructure.

## Tech stack
➔ Language: Python ➔ Services: AWS S3, AWS Cloud9, AWS CDK, AWS EMR, Power BI, Apache Hive

Key Takeaways
- Understanding the Sales dataset
- Understanding the AWS CDK
- Installation of AWS CDK and its various commands
- Advantages of Serverless technologies
- Creating an AWS Cloud9 environment
- Understanding the difference between AWS and Azure
- Difference between UUID and NanoID
- Difference between Hive and Spark
- Understanding the S3 Bucket deployment stack
- Understanding the Security stack
- Understanding the Hive script to create tables
- Understanding the Hive script to transform da.

## How to run
```bash
pip install -r Code/requirements-dev.txt
python Code/app.py
```

## Project structure
```
.gitignore
Code/
  .gitignore
  INSTRUCTIONS.md
  README.md
  app.py
  bucket_deployment_stack/
    bucket_deployment_stack.py
  emr_cluster_stack/
    emr_cluster_stack.py
  requirements-dev.txt
  requirements.txt
  scripts/
    generate_nanoid.py
  security_stack/
    security_stack.py
  source.bat
  tests/
    __init__.py
    unit/
README.md
```

## Credits
Based on a ProjectPro guided project.
