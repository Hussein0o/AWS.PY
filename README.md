1. What is Boto3?

    Boto3 is the Amazon Web Services (AWS) SDK for Python.

    Allows Python developers to write software that uses AWS services like EC2, S3, and more.

2. Core Components of Boto3

    Clients: Low-level service access. E.g., boto3.client('ec2')

    Resources: Higher-level, object-oriented. E.g., boto3.resource('ec2')

    Session: Allows you to manage multiple AWS accounts/environments.

3. Accessing EC2 & VPC

    describe_vpcs(): Returns details of all VPCs.

    describe_instances(): Returns metadata about EC2 instances.

4. Output Handling

    Use Python's json module to serialize data.

    Timestamps help version your output.

5. Resources Used

    Official Boto3 Docs

    AWS Python SDK Guide

    YouTube: AWS Boto3 Crash Course

    Tutorials on Real Python, FreeCodeCamp, and Medium.

6. Challenges Faced

    Understanding the structure of describe_instances() response.

    Parsing nested lists and dictionaries.

7. Tips

    Always include a region (region_name) explicitly.

    Use json.dumps(data, indent=4, default=str) to make AWS data readable.
