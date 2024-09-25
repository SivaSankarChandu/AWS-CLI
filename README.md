AWS CLI Configuration

Before you can interact with AWS S3 using the CLI, you need to configure the AWS CLI with your credentials. Follow these steps:

Install AWS CLI: Make sure you have the AWS CLI installed on your system.

Run Configuration Command:

$aws configure

This command will prompt you to enter the following details:

AWS Access Key ID: This is like your username for AWS.
AWS Secret Access Key: This is your password for AWS (Keep it private!).
Default region name: The AWS region where you want to operate, e.g., us-east-1.
Default output format: The format for CLI output (e.g., json, text, table).

Role-Based Access (If needed):

If you're using an IAM role instead of user access keys, you can assign the role to your EC2 instance or use assume-role commands for access.
After configuring, you can use various aws s3 commands to interact with your S3 buckets, such as uploading, downloading, and listing files.

This configuration ensures your system knows who you are and what permissions you have when accessing AWS services.
