
### AWS CloudTrail
    find who made the changes
    Provides governance, compliance and audit for your AWS Account
    Get an history of events / API calls made within your AWS Account by: Console, SDK, CLI, AWS Services
    Can put logs from CloudTrail into CloudWatch Logs or S3
    If a resource is deleted in AWS, investigate CloudTrail first!


### CloudTrail Events Retention
    Events are stored for 90 days in CloudTrail To keep events beyond this period, log them to S3 and use Athena



### CloudTrail Insights

    Enable CloudTrail Insights to detect unusual activity in your account: 
        inaccurate resource provisioning 
        hitting service limits
        Bursts of AWS IAM actions
        Gaps in periodic maintenance activity


### CloudTrail Events
    Operations that are performed on resources in your AWS account
        Configuring security (IAM AttachRolePolicy)
        Configuring rules for routing data (Amazon EC2 CreateSubnet)
        Setting up logging (AWS CloudTrail CreateTrail)


    By default, trails are configured to log management events.
    Can separate Read Events (that don’t modify resources) from Write Events (that may modify resources)


    Data Events:
        By default, data events are not logged (because high volume operations)
        Amazon S3 object-level activity (ex: GetObject, DeleteObject, PutObject): can separate Read and Write Events
        AWS Lambda function execution activity (the Invoke API)
