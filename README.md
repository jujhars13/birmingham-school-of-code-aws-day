# Birmingham School Of Code AWS Day
Birmingham School of Code - Cohort 4 AWS day
**2020-12-03**

## Objective

Give SOC students a feel for AWS and then be able to deploy an application to EC2 and a static site to S3 + Cloudfront.
Give as much hands on as possible.

## Timetable

item | time
:- | -:
Start | 9:15am
Break | 1:30pm - 2:20pm
Finish | ~4:00pm

## Syllabus

- Admin - create slack channel, split up into 6 groups, give each pair a (/zoom breakout room), and aws account creds from log in spreadsheet
- Intro - the team, who we are and our journeys into software engineering (go through your Linkedin profile)
-

- Intro to AWS Cloud ~ 10 mins https://www.slideshare.net/CloudHesive/aws-101-an-introduction-to-the-amazon-cloud
  - Explore AWS a bit and go over services

- EC2 - deeper dive, create instance
  **Joint exercise**
  Break up into your groups:
  - Spin up and configure an ec2 instance in dev VPC of choice
  - Get nodejs 14+ installed
  - Get a rudimentary NodeJS web app running.  Sample one in `/app`
  - Poke holes in the security group to the world
  - Access your API from the world
    - observe your "access logs"

**Break for guest lecturer**

- S3 + Cloudfront - deeper dive, create instance
  - what is a CDN ?
  **Joint exercise**
  Break up into your groups:
  - create an s3 bucket
  - configure it for web access
  - test access to bucket
  - create a cloudfront distribution
  - wire up s3 bucket to cloudfront
  - test cloudfront distribution

**Lecture**
- a career in DevOps
  - DevSecOps principles
  - Cloud Vs DevOps
  - What is it that we do, what does our day to day look like?
- DevSecOps Learning path:
  - [https://aws.amazon.com/training/path-devops/]()
  - [https://cloudacademy.com/library/devops/learning-paths/]()
  - [https://acloud.guru/learn/aws-technical-essentials]()
  - Resource: Free tier on AWS
- Open Q&A around Cloud, Dev[Sec]Ops, SRE or anything else!
- Quick Retro
- Clean up AWS accounts down instances, code9, users and groups
