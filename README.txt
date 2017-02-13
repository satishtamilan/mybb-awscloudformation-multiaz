#### MyBBAWS Infrastructure

#### Overview

This is a **complete AWS CloudFormation template** (along with additional required source codes
residing in the public GitHub repository https://github.com/satishtamilan/mybb-awscloudformation-multiaz) for
running the MyBB application on a scalable, highly-available and secure infrastructure using the Aurora DB.

#### Running the stack

To run this project in an AWS Account do the following:

- Create an EC2 KeyPair (required for SSH access, can't be automated by CF);
- Launch a stack from this template with CloudFormation;
- Go to the URL in the "WWWBalancerDNSName" output variable for the live MyBB application.

- MyBB application Administrator Account:
    - Username: admin
    - Password: 1234

- If you need any other access please [contact me](mailto:valeriupalos@gmail.com)!

## See the detailed documentation!

This file is only an excerpt of the documentation found in "Design/Documentation.md/pdf".

Thank you!
