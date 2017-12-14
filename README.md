# ansible-cloudwatch-metrics

## This is a playbook to install Amazon CloudWatch Monitoring Scripts 

> Monitoring Memory and Disk Metrics for Amazon EC2 Linux Instances

>The Amazon CloudWatch Monitoring Scripts for Amazon Elastic Compute Cloud (Amazon EC2) Linux-based instances demonstrate how to produce and consume Amazon CloudWatch custom metrics. These sample Perl scripts comprise a fully functional example that reports memory, swap, and disk space utilization metrics for a Linux instance. You can download the Amazon CloudWatch Monitoring Scripts for Linux from the AWS sample code library.



http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/mon-scripts.html


- OS : AmazonLinux
- Ansible : 2.x
- AWS EC2 Instance with EC2 Role - CloudWatchFullAccess

Please ensure that your EC2 has an attached role to Cloudwatch service.
