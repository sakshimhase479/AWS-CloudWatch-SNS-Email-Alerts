# AWS-CloudWatch-SNS-Email-Alerts
EC2 CPU monitoring and automated email alerts using CloudWatch and SNS.

AWS CloudWatch Monitoring and SNS Email Alert System

Project Overview

This project monitors CPU utilization on an Amazon EC2 instance using Amazon CloudWatch. When CPU utilization exceeds a configured threshold, a CloudWatch alarm triggers an Amazon SNS notification to send an email alert.

AWS Services Used

- Amazon EC2
- Amazon CloudWatch
- Amazon SNS
- Linux

Project Workflow

1. Launch an EC2 instance.
2. Monitor CPU utilization using CloudWatch.
3. Configure a CloudWatch alarm with a CPU utilization threshold.
4. Create an SNS topic and confirm the email subscription.
5. Connect the SNS topic to the CloudWatch alarm.
6. Generate CPU load and verify the email notification.

Key Learnings

- EC2 monitoring using CloudWatch metrics
- CloudWatch alarm configuration
- SNS email notifications
- Automated alerting for high CPU utilization

Outcome

Successfully demonstrated an automated monitoring and email alert workflow to help identify high CPU utilization on an EC2 instance.

Author

Sakshi Dattatray Mhase
