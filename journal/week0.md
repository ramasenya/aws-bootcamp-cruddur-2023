# Week 0 — Billing and Architecture

## Required Homework
Download and run the AWS CLI MSI installer for Windows (64-bit):
https://awscli.amazonaws.com/AWSCLIV2.msi
Wait for the installation to prompt to guide you through the installation process
run this command aws --version on the windows command line to check the cli version
create access key and secret access key on the management console
run this command aws configure on windows command line and provide credentials
$ aws configure
AWS Access Key ID [None]: ""
AWS Secret Access Key [None]: ""
Default region name [None]: us-west-2
Default output format [None]: json
setup MFA the aws managemaent console,I used the DUO app

### Creating a billing alarm
Open the CloudWatch console at https://console.aws.amazon.com/cloudwatch/
Choose Alarms, and then choose All alarms from the navigation pane
Choose Create alarm.
Choose Select metric. In Browse, choose Billing, and then choose Total Estimated Charge
Select the box for the EstimatedCharges metric, and then choose Select metric.
For Statistic, choose Maximum.
For Threshold type, choose Static.


#### Lucid Diagram
https://lucid.app/lucidchart/1bd42f56-61b5-4d26-8dee-4f09dc391622/edit?viewport_loc=190%2C1088%2C1024%2C649%2C0_0&invitationId=inv_0bdf2747-e893-41b2-af5d-dbb4e071e3a6
