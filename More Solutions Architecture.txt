
### Fan Out Pattern: deliver to multiple SQS

### S3 Event Notifications

### S3 Event Notifications with Amazon EventBridge
    - Advanced filtering options with JSON rules (metadata, object size, name...)
    - Multiple Destinations – ex Step Functions, Kinesis Streams / Firehose…
    - EventBridge Capabilities – Archive, Replay Events, Reliable delivery

### Amazon EventBridge – Intercept API Calls

### Blocking an IP address
    - EC2 Instance Public IP + Optional Firewall Software in EC2
    - Blocking an IP address – ALB + web application firewall (WAF)
    - Blocking an IP address – ALB, CloudFront web application firewall (WAF)


### High Performance Computing (HPC)
    - The cloud is the perfect place to perform HPC
    - Perform genomics, computational chemistry, financial risk modeling, weather prediction, machine learning, deep learning, autonomous driving



### Data Management & Transfer

    - AWS Direct Connect:
        Move GB/s of data to the cloud, over a private secure network
    
    - Snowball & Snowmobile
        Move PB of data to the cloud
    
    - AWS DataSync
        Move large amount of data between on-premises and S3, EFS, FSx for Windows



### Compute and Networking
    - EC2 Instances: CPU optimized, GPU optimized
    - Cluster for good network performance

### Compute and Networking

    - EC2 Enhanced Networking (SR-IOV)
        Higher bandwidth, higher PPS (packet per second), lower latency
        Option 1: Elastic Network Adapter (ENA) up to 100 Gbps
        Option 2: Intel 82599 VF up to 10 Gbps – LEGACY

    - Elastic Fabric Adapter (EFA)
        Improved ENA for HPC, only works for Linux
        Great for inter-node communications, tightly coupled workloads
        Leverages Message Passing Interface (MPI) standard
        Bypasses the underlying Linux OS to provide low-latency, reliable transport


### Storage

    - Instance-attached storage:
        EBS: scale up to 256,000 IOPS with io2 Block Express
        Instance Store: scale to millions of IOPS, linked to EC2 instance, low latency

    - Network storage:
        Amazon S3: large blob, not a file system
        Amazon EFS: scale IOPS based on total size, or use provisioned IOPS
        Amazon FSx for Lustre:
            HPC optimized distributed file system, millions of IOPS
            Backed by S3



### Automation and Orchestration

    - AWS Batch
        AWS Batch supports multi-node parallel jobs, which enables you to run single jobs that span multiple EC2 instances.
        Easily schedule jobs and launch EC2 instances accordingly

    - AWS ParallelCluster
        Open-source cluster management tool to deploy HPC on AWS
        Automate creation of VPC, Subnet, cluster type and instance types
        Ability to enable EFA on the cluster (improves network performance)

