## AWS Project - Build a Full End-to-End Web Application with 7 Services

Build a ride sharing app (for unicorns!), pulling from the AWS Wild Rydes sample project.  I used seven different AWS  services: CodeCommit, Amplify, Cognito, Lambda, IAM, API Gateway and DynamoDB. 

## AWS Project Overview

WILDRYDES is basically an Uber oryt except for unicorns, with some good static content, incorporate user registration and and log in and be able to be able to work with some map functionality, so that if we were in Seattle let's say we could request a unicorn just by clicking on the map we'll request unicorn.

It's really a great app for tying together a bunch of different services in AWS and you'll actually have a working application when you're done that you could share with friends or family.


## The Application Architecture

![Screenshot](/images/aws_archi.PNG)


![Screenshot](/images/aws_img_01.jpg)

### [🌐 LIVE SITE](https://master.d3rj3myz3ltnf7.amplifyapp.com/)


Features:

- A way to store/update/pull code
- A way to handle permissions for code
- A place to host website and make updates
- A way for users to register and log in
- A way to do ride sharing functionality
- Somewhere to store/return ride results
- A way to invoke ride sharing functionality


## Source Code

This is an AWS sample project, all of the code is available for download.

Command to copy code from AWS’s S3 bucket (from CloudShell command line): 

```bash
    aws s3 cp s3://wildrydes-[your_region_name, like us-west-2]/WebApplication/1_StaticWebHosting/website ./ --recursive
```

## Cost
All services used are eligible for the [AWS Free Tier](https://aws.amazon.com/free/).  However, charges will incur at some point so it's recommended that you shut down resources after completing this tutorial.

