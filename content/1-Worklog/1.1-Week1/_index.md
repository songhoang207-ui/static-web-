---
title: "Week 1 Worklog"
date: 2026-10-01
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Week 1 Objectives:

* Host a static website using S3 with ci/cd using Codepipeline.
* Build and deploy serverless contact form.
* Understand and integrate basic AWS services for frontend hosting and backend processing.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 4   | - **Static Website Hosting setup:** <br>&emsp; + Create and configure an S3 bucket for static website hosting <br>&emsp; + Configure custom domain DNS routing using Amazon Route 53                   | 30/09/2026 | 30/09/2026      | <https://cloudjourney.awsstudygroup.com/>, <https://docs.aws.amazon.com/> |
| 5   | - **CI/CD Pipeline Implementation:** <br>&emsp; + Set up AWS CodePipeline <br>&emsp; + Automate frontend deployment to push code changes automatically from the repository to S3                       | 01/10/2026 | 01/10/2026      | <https://cloudjourney.awsstudygroup.com/>, <https://docs.aws.amazon.com/> |
| 6   | - **Serverless Database & IAM setup:** <br>&emsp; + Design and provision a DynamoDB table to store user submissions <br>&emsp; + Create IAM executional role and policies with least privilege for Lambda access  | 02/10/2026 | 02/10/2026      | <https://cloudjourney.awsstudygroup.com/>, <https://docs.aws.amazon.com/> |
| 6   | - **Serverless Backend (Contact Form):** <br>&emsp; + Develop an AWS Lambda function to process form payload <br>&emsp; + Set up API Gateway to connect the frontend to the Lambda function | 02/10/2026 | 02/10/2026      | <https://cloudjourney.awsstudygroup.com/>, <https://docs.aws.amazon.com/> |


### Week 1 Achievements:

* **Hosted a Static Website with a CI/CD Pipeline:** 
  * Successfully configured S3.
  * Automated the deployment lifecycle using AWS CodePipeline, allowing for seamless and automatic frontend updates upon code commits from github.

* **Built a Serverless Contact Form:** 
  * Deployed a fully functional, decoupled serverless backend to securely receive, process, and store user inquiries.
  * Successfully integrated API Gateway to expose RESTful endpoints, triggering AWS Lambda for data processing, and storing the payload in DynamoDB.
  * Applied security best practices by configuring IAM roles to manage secure execution permissions between services.