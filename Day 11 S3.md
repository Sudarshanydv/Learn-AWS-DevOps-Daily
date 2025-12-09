📌 What is Amazon S3?

Amazon S3 (Simple Storage Service) is a fully managed object storage service in AWS used to store and retrieve data like images, videos, backups, logs, website files, etc.

⭐ Key Features of S3
Feature                     Meaning
-------------------------------------------------------------
Scalable                   Stores unlimited data
Secure                     Access controlled by IAM, bucket policies, encryption
Durable                    99.999999999% (11 9’s) durability
High Availability          Data automatically stored across multiple AZs
Cost-effective             Pay only for what you use
Versioning                 Keep multiple versions of same file
Lifecycle Policies         Automatically move or delete data to save cost
Static Website Hosting     Can host static websites (HTML, CSS, JS)

🔹 S3 Storage Classes (important for DevOps interviews)
Class                       Usage
----------------------------------------------------
S3 Standard                Frequently accessed data
S3 Standard-IA             Infrequent access, cheaper
S3 One Zone-IA             Stored in single AZ, lower cost
S3 Glacier / Deep Archive  Long-term backups, very low cost
S3 Intelligent-Tiering     Automatically moves data between tiers

🔐 S3 Security
- IAM Roles & Policies
- Bucket Policies
- S3 Block Public Access
- Encryption:
  - SSE-S3
  - SSE-KMS
  - Client-side encryption

🔁 S3 in DevOps Usage
DevOps Task                      How S3 Helps
---------------------------------------------------------------
CI/CD pipeline artifacts        Store build files (ZIP, JAR, etc.)
Backup & Disaster Recovery      EBS/RDS snapshot backups
Hosting static websites         React/Angular websites
Logs storage                    CloudTrail, ELB, Lambda logs
Terraform & CloudFormation      Store state files in S3
