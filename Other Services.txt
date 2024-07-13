### CloudFormation
    CloudFormation is a declarative way of outlining your AWS Infrastructure, for any resources
    Infrastructure as code
    

### CloudFormation – Service Role
    Give ability to users to create/update/delete the stack resources even if they don’t have permissions to work with the resources in the stack
    User must have iam:PassRole permissions


### Amazon Simple Email Service
    Fully managed service to send emails securely, globally and at scale


### Amazon Pinpoint
    Scalable 2-way (outbound/inbound) marketing communications service
    Supports email, SMS, push, voice, and in-app messaging


### Systems Manager – SSM Session Manager
    Allows you to start a secure shell on your EC2 and on-premises servers
    No SSH access, bastion hosts, or SSH keys needed
    No por t 22 needed (better security)


### Systems Manager – Run Command
    Execute a document (= script) or just run a command
    Run command across multiple instances (using resource groups)


### Systems Manager – Patch Manager
    Automates the process of patching managed instances
    OS updates, applications updates, security updates


### Systems Manager – Maintenance Windows
    Defines a schedule for when to perform actions on your instances
    Example: OS patching, updating drivers, installing software, …


### Systems Manager - Automation
    Simplifies common maintenance and deployment tasks of EC2 instances and other AWS resources
    Examples: restart instances, create an AMI, EBS snapshot
    Automation Runbook – SSM Documents to define actions preformed on your EC2 instances or AWS resources (pre-defined or custom)


### Cost Explorer
    Visualize, understand, and manage your AWS costs and usage over time
    Create custom reports that analyze cost and usage data.


### AWS Cost Anomaly Detection
    Continuously monitor your cost and usage using ML to detect unusual spends



### AWS Batch
    Fully managed batch processing at any scale
    Batch jobs are defined as Docker images and run on ECS


### Batch vs Lambda

    Lambda:
        Time limit
        Limited runtimes
        Limited temporary disk space
        Serverless

    Batch:
        No time limit
        Any runtime as long as it’s packaged as a Docker image
        Rely on EBS / instance store for disk space
        Relies on EC2 (can be managed by AWS)


### Amazon AppFlow
    Fully managed integration service that enables you to securely transfer data between Software-as-a-Service (SaaS) applications and AWS
    Sources: Salesforce, SAP, Zendesk, Slack, and ServiceNow
    Destinations: AWS services like Amazon S3, Amazon Redshift or non- AWS such as SnowFlake and Salesforce


### AWS Amplify - web and mobile applications
    A set of tools and services that helps you develop and deploy scalable full stack web and mobile applications

