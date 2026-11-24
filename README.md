# AWS Cloud-Based Application

## Project Objective
To build and deploy a cloud-based application using AWS services.

## AWS Services
- AWS IAM
- Amazon EC2
- Amazon S3
- Amazon CloudWatch
- AWS Budgets

## Project Architecture

                    CUSTOMER
                       |
                       v
                  CLOUDFRONT
                       |
                       v
                    AMAZON S3
                 (Website hosting)
                       |
                       v
                  API GATEWAY
                       |
                       v
                 AWS LAMBDA
              (Application logic)
                       |
                       v
                  DYNAMODB
             (Complaint database)

        IAM - Access and permissions
        CLOUDWATCH - Logs and monitoring


## Implementation Steps
1. Configure AWS IAM.
2. Create EC2 instance.
3. Configure S3 bucket.
4. Deploy the application.
5. Configure monitoring and alerts.


## Monthly Budget
$5 USD
