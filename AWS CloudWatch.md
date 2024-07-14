


### Amazon CloudWatch Metrics
    Metric is a variable to monitor
    Can create CloudWatch dashboards of metrics
    Can create CloudWatch Custom Metrics

### CloudWatch Metric Streams
    Continually stream CloudWatch metrics to a destination of your choice, with near-real-time delivery and low latency.

### CloudWatch Logs
    Log groups: arbitrary name, usually representing an application
    Log stream: instances within application / log files / containers
    Can define log expiration policies (never expire, 1 day to 10 years…)


### CloudWatch Logs Insights
    Search and analyze log data stored in CloudWatch Logs
    Can query multiple Log Groups in different AWS accounts

### CloudWatch Logs – S3 Export
    The API call is CreateExport Task

### CloudWatch Logs Subscriptions
    Get a real-time log events from CloudWatch Logs for processing and analysis
    Subscription Filter – filter which logs are events delivered to your destination
    Cross-Account Subscription – send log events to resources in a different AWS account (KDS, KDF)


### CloudWatch Logs Aggregation Multi-Account & Multi Region


### CloudWatch Logs for EC2
    By default, no logs from your EC2 machine will go to CloudWatch
    You need to run a CloudWatch agent on EC2 to push the log files you want
    Make sure IAM permissions are correct


### CloudWatch Logs Agent & Unified Agent
    
    - CloudWatch Logs Agent
        Old version of the agent
        Can only send to CloudWatch Logs
    
    - CloudWatch Unified Agent
        Collect additional system-level metrics such as RAM, processes, etc…
        Collect logs to send to CloudWatch Logs
        Centralized configuration using SSM Parameter Store
        Collected directly on your Linux server / EC2 instance: CPU, Disk metrics, RAM, Netstat, Processes, Swap Space


### CloudWatch Alarms
    Alarms are used to trigger notifications for any metric
    Alarm States:
        OK
        INSUFFICIENT_DATA
        ALARM


### CloudWatch Alarm Targets
    Stop, Terminate, Reboot, or Recover an EC2 Instance
    Trigger Auto Scaling Action
    Send notification to SNS (from which you can do pretty much anything)


### CloudWatch Alarms – Composite Alarms
    CloudWatch Alarms are on a single metric
    Composite Alarms are monitoring the states of multiple other alarms


### EC2 Instance Recovery
    Status Check:
        Instance status = check the EC2 VM
        System status = check the underlying hardware
    Recovery: Same Private, Public, Elastic IP, metadata, placement group


### CloudWatch Alarm: good to know
    Alarms can be created based on CloudWatch Logs Metrics Filters CloudWatch Metric Filter
    
    To test alarms and notifications, set the alarm state to Alarm using CLI
        aws cloudwatch set-alarm-state --alarm-name "myalarm" --state-value ALARM --state-reason "testing purposes"



### CloudWatch Insights and Operational Visibility
    - CloudWatch Container Insights
        ECS, EKS, Kubernetes on EC2, Fargate, needs agent for Kubernetes Metrics and logs

    - CloudWatch Lambda Insights
        Detailed metrics to troubleshoot serverless applications

    - CloudWatch Contributors Insights
        Find “Top-N” Contributors through CloudWatch Logs

    - CloudWatch Application Insights
        Automatic dashboard to troubleshoot your application and related AWS services
