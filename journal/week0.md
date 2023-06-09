# Week 0 — Billing and Architecture

## Required Tasks

### Watch the videos
I was able to watch the live stream for week 0, Chirag's tutorial on spend considerations and Ashish's tutorial on security consideration.

### AWS Requirements
I was able to create an IAM user with full administrator access.

I was able to use aws cloudshell.

Also, I was able to generate security credentials on my aws account which are the access key and security key.

I was able to install the aws cli on gitpod cde and I can reference that with the link to the [gitpod yaml file](https://github.com/bennie-jr/aws-bootcamp-cruddur-2023/blob/main/.gitpod.yml) in repo

### Create a Budget
I created a budget with a spend of $5 because i cannot afford any kind of spend. I also created just one budget because i did not want to exceed the free tier limit on budgets.
![proof of budget creation](assets/week0-create%20budget.png)

### Create a Billing Alarm
Created a Billing Alarm with aws cloudwatch on my aws account to trigger when daily estimated charges exceed $1.
![proof of billing alarm](assets/week0-billing%20alarm.png)

### Recreate Conceptual Diagram on Lucid Charts
![Conceptual Diagram on Lucid Charts](assets/Week0-Conceptual%20diagram%20lucid%20charts.png)

[Lucid Charts Shared link](https://lucid.app/lucidchart/ae9d7341-75f1-4709-921d-fed233aab17f/edit?viewport_loc=-3758%2C-975%2C2707%2C1387%2C0_0&invitationId=inv_3f9d8550-2fb0-4b79-b5d3-67010a08cb81)

### Recreate Logical Architectural Diagram on Lucid Charts
![Logical Architectural Diagram on Lucid Charts](assets/Week0-logical%20Archictectural%20Diagram.png)

[Lucid Charts Shared Link](https://lucid.app/lucidchart/781b1b56-bd8a-4e3e-8283-902f39c8e213/edit?viewport_loc=162%2C-167%2C2707%2C1387%2C0_0&invitationId=inv_2652ad75-d301-4785-bcc1-be2f2c7387a6)


## Homework Challenges

### Root Credential Removal, Set MFA and IAM Role
I successfully destroyed my root user credentials , set mfa on my account and create an IAM role for my user

###  Setup EventBridge To Health Dashboard To SNS To Send Service Health Notification
![EventBridge to Health Dashboard to SNS](assets/Week0-eventbridge-sns.png)

### AWS Well Architected Tool (No specialized lens) Questions Review
I finished reviewing all the questions under Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability.

### Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts
![CI/CD Logical pipeline](assets/ciicd%20pipeline.png)
[Lucid Charts Shared Link](https://lucid.app/lucidchart/368e8e07-2a3c-4f9d-be83-8300c56fcf9e/edit?viewport_loc=-548%2C700%2C2712%2C1387%2C0_0&invitationId=inv_7a3ae2d9-a832-4158-9ed3-bae00e2bd448)


