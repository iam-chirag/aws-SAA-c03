

### AWS Config

    Helps with auditing and recording compliance of your AWS resources
    Questions that can be solved by AWS Config:
        Is there unrestricted SSH access to my security groups?
        Do my buckets have any public access?
        How has my ALB configuration changed over time?


### Config Rules
    Can use AWS managed config rules (over 75)
    Can make custom config rules (must be defined in AWS Lambda)
    Rules can be evaluated / triggered:
        For each config change
        And / or: at regular time intervals


### AWS Config Resource
    View compliance of a resource over time
    View configuration of a resource over time
    View CloudTrail API calls of a resource over time



### Config Rules – Remediations
    Automate remediation of non-compliant resources using SSM Automation Documents


### Config Rules – Notifications
    Use EventBridge to trigger notifications when AWS resources are non - compliant



### CloudWatch / CloudTrail / Config

    CloudWatch
        Performance monitoring (metrics, CPU, network, etc…) & dashboards
        Events & Alerting
        Log Aggregation & Analysis

    CloudTrail
        Record API calls made within your Account by everyone
        Can define trails for specific resources
        Global Service

    Config
        Record configuration changes
        Evaluate resources against compliance rules
        Get timeline of changes and compliance











