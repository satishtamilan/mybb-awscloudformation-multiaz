# MyBBAWS Infrastructure

#                                   
#  NOTE: Please see the fixed video clip in the Video folder! 
#                                                             

## Overview

This is a **complete AWS CloudFormation template** (along with additional required source codes
residing in the public GitHub repository https://github.com/vpalos/cloudformation-mybb/) for
running the MyBB application on a scalable, highly-available and secure infrastructure.

### Running the stack

To run this project in an AWS Account do the following:

- Create an EC2 KeyPair (required for SSH access, can't be automated by CF);
- Launch a stack from this template with CloudFormation;
- ...drink coffee...
- Go to the URL in the "WWWBalancerDNSName" output variable for the live MyBB application.

## Evaluation Access Account

- AWS Console access:
    - URL: https://851806062413.signin.aws.amazon.com/console
    - Username: observer
    - Password: LEoZ$uSy6]Wr
    - Notes:
        - Currently there are **2 stacks** deployed in region **us-east-1 (N. Virginia)**.
        - Read-only access granted for: **CloudFormation, EC2, RDS, S3, SNS and CloudWatch**.

- MyBB application Administrator Account:
    - Username: admin
    - Password: 1234

- If you need any other access please [contact me](mailto:valeriupalos@gmail.com)!

## See the detailed documentation!

This file is only an excerpt of the documentation found in "Design/Documentation.md/pdf".

Thank you!
