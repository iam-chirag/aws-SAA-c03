
### Disaster Recovery Overview
    Disaster recovery (DR) is about preparing for and recovering from a disaster
    RPO: Recovery Point Objective
    RTO: Recovery Time Objective


### Disaster Recovery Strategies

    - Backup and Restore (High RPO)
    
    - Pilot Light
        A small version of the app is always running in the cloud

    - Warm Standby
        Full system is up and running, but at minimum size
    
    - Hot Site / Multi Site Approach (High RTO)
        Full Production Scale is running AWS and On Premise



### Disaster Recovery Tips
    Backup
    High Availability
    Replication
    Automation
    Chaos


### DMS – Database Migration Service
    Quickly and securely migrate databases to AWS, resilient, self healing


### AWS Schema Conversion Tool
    Convert your Database’s Schema from one engine to another


### AWS DMS – Multi-AZ Deployment
    When Multi-AZ Enabled, DMS provisions and maintains a synchronously stand replica in a different AZ


### RDS & Aurora MySQL Migrations
    Option 1: DB Snapshots from RDS MySQL restored as MySQL Aurora DB
    Option 2: Create an Aurora Read Replica from your RDS MySQL, and when the replication lag is 0, promote it as its own DB cluster (can take time and cost $)


### RDS & Aurora PostgreSQL Migrations
    Option 1: DB Snapshots from RDS PostgreSQL restored as PostgreSQL Aurora DB
    Option 2: Create an Aurora Read Replica from your RDS PostgreSQL, and when the replication lag is 0, promote it as its own DB cluster (can take time and cost $)



### AWS Backup
    Centrally manage and automate backups across AWS services


### AWS Backup Vault Lock
    Enforce a WORM (Write Once Read Many) state for all the backups that you store in your AWS Backup Vault
    Even the root user cannot delete backups when enabled


### VMware Cloud on AWS

    Some customers use VMware Cloud to manage their on-premises Data Center
    Migrate your VMware vSphere-based workloads to AWS


### AWS Application Discovery Service
    
    Plan migration projects by gathering information about on-premises data centers
    Server utilization data and dependency mapping are important for Migrations

    - Agentless Discovery (AWS Agentless Discovery Connector)
        VM inventory, configuration, and performance history such as CPU, memory, and disk usage

    - Agent-based Discovery (AWS Application Discovery Agent)
        System configuration, system performance, running processes, and details of the network connections between systems



### AWS Application Migration Service
    Lift-and-shift (rehost) solution which simplify migrating applications to AWS



### On-Premise strategy with AWS
    Ability to download Amazon Linux 2 AMI as a VM (.iso format)
    VM Import / Export
    AWS Application Discovery Service
    AWS Database Migration Service (DMS)
    AWS Server Migration Service (SMS)
    