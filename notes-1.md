**Snowball Edge** is comes with computing capabilities and allows you to pre-process the data while it's being moved into Snowball.

**Tape Gateway** provides a virtual tape infrastructure in AWS cloud that integrates with existing backup software applications.

**Volume Gateway** presents cloud-backed storage volumes to your on-premises applications as iSCSI devices.

**S3 File Gateway** presents a file interface to store objects in Amazon S3 buckets, allowing you to store and retrieve files directly using standard file protocols.

**A persistent file system** is designed for storing data that needs to persist beyond the lifespan of individual compute instances.

**A scratch file system** typically refers to temporary storage that is used for short-term or transient data storage needs.

**FSx File Gateway** enables you to seamlessly integrate on-premises applications with Amazon FSx for Windows File Server, which is a fully managed Windows file system in the cloud. It provides a hybrid cloud storage solution where your on-premises applications can access data stored in FSx for Windows File Server without needing to modify your applications or workflows.

**AWS DataSync** is an online data transfer service that simplifies, automates, and accelerates moving data between on-premises storage systems and AWS Storage services, as well as between AWS Storage services.


• **S3:** Object Storage
• **S3 Glacier:** Object Archival
• **EBS volumes:** Network storage for one EC2 instance at a time
• **Instance Storage:** Physical storage for your EC2 instance (high IOPS)
• **EFS:** Network File System for Linux instances, POSIX filesystem
• **FSx for Windows:** Network File System for Windows servers
• **FSx for Lustre:** High Performance Computing Linux file system
• **FSx for NetApp ONTAP:** High OS Compatibility
• **FSx for OpenZFS:** Managed ZFS file system
• **Storage Gateway:** S3 & FSx File Gateway, Volume Gateway (cache & stored), Tape Gateway
• **Transfer Family:** FTP, FTPS, SFTP interface on top of Amazon S3 or Amazon EFS
• **DataSync:** Schedule data sync from on-premises to AWS, or AWS to AWS
• **Snowcone / Snowball / Snowmobile:** to move large amount of data to the cloud, physically
• **Database:** for specific workloads, usually with indexing and querying

=============================================================================


The capacity limits of a **Kinesis data stream** are defined by the number of shards within the data stream. The limits can be exceeded by either data throughput or the number of reading data calls. Each shard allows for 1 MB/s incoming data and 2 MB/s outgoing data. You should increase the number of shards within your data stream to provide enough capacity.


**Amazon Cognito** lets you add user sign-up, sign-in, and access control to your web and mobile apps quickly and easily. Amazon Cognito scales to millions of users and supports sign-in with social identity providers, such as Apple, Facebook, Google, and Amazon, and enterprise identity providers via SAML 2.0 and OpenID Connect.

=============================================================================

**Amazon SQS** allows you to retain messages for days and process them later, while we can take down our EC2 instances.

**Amazon Kinesis Data Streams (KDS)** is a massively scalable and durable real-time data streaming service. It can continuously capture gigabytes of data per second from hundreds of sources such as website clickstreams, database event streams, financial transactions, social media feeds, IT logs, and location-tracking events.


=============================================================================


**Retention Government Mode** is designed to meet the requirements of governmental agencies or other organizations that need to ensure strict immutability and compliance with regulatory standards.

**Retention Compliance Mode** is also aimed at ensuring data immutability and compliance with regulatory standards, but it may offer some flexibility compared to Government Mode.

**Legal Hold** is a feature that allows organizations to preserve data for legal or investigative purposes.
