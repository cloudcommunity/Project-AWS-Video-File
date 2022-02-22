# Project "AWS Video File Upload & Process"

AWS video file upload and process.

Project code: CSNPJ0001

## Goal

To create a pipeline to accomplish the tasks listed in the "use case" chapter.

## Prerequisites

- Cloud provider: AWS

## Project Team

- @lilitZak - project lead
- @karentamrazyan - project coordinator
- new members can apply via https://forms.gle/BkxWRvagVJ9QL1yx6

## Use Case

1. provide an API to uploaf a video file (up to 1GB) to an S3 bucket. It should ask for an email address.
2. event should be generated on file upload, then lambda function will ping an ec2 instance and supply the address of the file to it
3. ec2 instance is like a black box. It process the video file.

Question: should the file be locally copied to the ec2 instance or not? Should be answered during the solution finding process.

4. send email with a report to the provided email

Store everything is a database.

## Images

![AWS_Project_1.png](https://github.com/cloudcommunity/Project-AWS-Video-File/blob/main/AWS_Project_1.png)

![AWS_Project_2.png](https://github.com/cloudcommunity/Project-AWS-Video-File/blob/main/AWS_Project_2.png)

![AWS_Project_3.png](https://github.com/cloudcommunity/Project-AWS-Video-File/blob/main/AWS_Project_3.png)

![AWS_Project_4.png](https://github.com/cloudcommunity/Project-AWS-Video-File/blob/main/AWS_Project_4.png)
