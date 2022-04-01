# aws-s3-public-website
# Basically we want to create S3 as public website and create IAM user who can manage content to this site.

    Description: "This template is used to create a single S3 bucket for basic object storage. Parameters 
                  provide the ability to use S3 canned ACLs, enable default encryption and enable object versioning.  On successful resource creation both the 
                  bucket url and arn will be exported and available for import in other CloudFormation 
                  templates.
                  Requirement 01: use AWS S3 as static website"

# Steps
# Login to Required AWS account where you need to setup this S3.

![image](https://user-images.githubusercontent.com/44979343/161304826-247e63ce-77b1-4252-acfb-48d97f49cec8.png)

![image](https://user-images.githubusercontent.com/44979343/161305978-2b9b4821-0229-4ab3-85be-007bc353b7c7.png)

![image](https://user-images.githubusercontent.com/44979343/161306521-2808e31b-f8e1-408f-985c-c88f2d033d8d.png)

