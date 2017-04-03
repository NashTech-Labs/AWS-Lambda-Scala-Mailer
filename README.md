# AWS-Lambda-Scala-Mailer

A Sample mailer function to notify on every AWS S3 action using AWS lambda. Here I have used AWS Lambda to demonstrate the serverless application.In this application one can get notified whenever action performed on S3 like DeleteObject,PutObject etc. with the help of Lambda handler.

# Prerequisites

1. Java 1.8
2. scala
3. sbt
4. AWS Account

# Getting the Project

https://github.com/abhisheknoldus/AWS-Lambda-Scala-Mail.git

# Create executable jar:

sbt assembly

# Steps to create AWS-Lambda function:

1. Login to your AWS account.
2. Create a lambda function.
3. Follow the steps and add trigger with S3.
4. Add environmental variable EMAIL=<your@example.com> and PASSWORD=yourmailpassword
5. Upload the excutable jar to lambda.

Now Test function with uploading an object to S3 bucket associated with AWS-lambda function.
