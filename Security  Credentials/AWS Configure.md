# AWS Configure

- aws configure is a command used to set up AWS credentials and default configurations for the AWS CLI (Command Line Interface).
- It allows you to specify the access keys, region, and output format so you can interact with AWS services programmatically.
- The aws configure command is essential for securely and efficiently managing AWS credentials, setting default configurations, and enabling seamless interaction with AWS services.

 # Why Use aws configure?
- Authentication: Stores AWS credentials securely for CLI interactions.
- Convenience: Eliminates the need to pass credentials in every command.
- Multi-Account Support: Allows switching between different AWS accounts using profiles.
- Region Specification: Defines the default AWS region to avoid specifying it in each command.
- Output Format: Sets the preferred output format (JSON, YAML, table, etc.).

# Command

      aws configure

# Output

     AWS Access Key ID [None]: AKIAIOSFODNN7EXAMPLE
     AWS Secret Access Key [None]: wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
     Default region name [None]: us-east-1
     Default output format [None]: json

- AWS Access Key ID:
  
     A unique key for authentication.
  
- AWS Secret Access Key:

    A private key used to sign API requests.
- Default region name:
  
    Example: us-east-1, ap-south-1.
  
- Default output format:
  
    Options: json, table, text. Default is json.
