Name : SADHANA S

REG.NO : 212224230234

EX -5 - AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

Aim

To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.

Requirements

AWS Console access CloudTrail service enabled S3 bucket (for storing logs) IAM permissions to view audit logs

Procedure

Step 1: Enable CloudTrail

Go to CloudTrail from AWS Console Click Trails > Create trail Name: CloudAuditTrail Apply trail to all regions Log events:

Management events: Read & Write Data events: S3, Lambda (optional) Create or select an S3 bucket for log storage Enable CloudWatch Logs integration (optional)

Step 2: Review Event History

Go to Event history Filter events by:

Username (IAM role or user) Event name (e.g., CreateBucket, TerminateInstances) Date/Time Resource type (e.g., S3, EC2)

Step 3: Download or Export Logs:

Use the Download CSV option to export logs Analyze logs in Excel/Sheets for reporting

Output:

![image](https://github.com/user-attachments/assets/df3efeb0-1de6-4233-aaf5-246a7f595a05)


Result

All AWS user activities, including volume creation, deletion, and permission changes, were successfully audited using CloudTrail.

