# Advanced Demo - Web Identity Federation

In this advanced demo series you will be implementing a simple serverless application which uses Web Identity Federation.  
The application runs using the following technologies

- S3 for front-end application hosting
- Google API Project as an ID Provider
- Cognito and IAM Roles to swap Google Token for AWS credentials

The application runs from a browser, gets the user to login using a Google ID and then loads all images from a private S3 bucket into a browser using presignedURLs.

This advanced demo consists of 6 stages :-

- STAGE 1 : Provision the environment and review tasks 
- STAGE 2 : Create Google API Project & Client ID
- STAGE 3 : Create Cognito Identity Pool
- STAGE 4 : Update App Bucket & Test Application
- STAGE 5 : Cleanup the account

![Architecture](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-cognito-web-identity-federation/ArchitectureEvolution.png)

## Instructions

- [Stage1](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/Stage1.md)
- [Stage2](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/Stage2.md)
- [Stage3](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/stage3.md)
- [Stage4](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/Stage4.md)
- [Stage5](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/stage5.md)



## 1-Click Installs
Make sure you are logged into AWS and in `us-east-1`  

- [WEBIDF](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/quickcreate?templateURL=https://learn-cantrill-labs.s3.amazonaws.com/aws-cognito-web-identity-federation/WEBIDF.yaml&stackName=WEBIDF)

## Video Guides

- [STAGE1](https://youtu.be/DyiJZz07g_E) - SETUP
- [STAGE2](https://youtu.be/wWQ8lgqa4fo) - Google API project
- [STAGE3](https://youtu.be/MXkqOgXkwRQ) - Cognito Identity Pool
- [STAGE4](https://youtu.be/YkDImYUcY3U) - Configure and Test Application
- [STAGE5](https://youtu.be/aJALTW-F24g) - Cleanup

## Architecture Diagrams

- [Overall - PNG](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ArchitectureEvolution.png)
- [Overall - PDF](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ArchitectureEvolution.pdf)

- [Stage1 - PNG](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE1.png)
- [Stage1 - PDF](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE1.pdf)
- [Stage2 - PNG](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE2.png)
- [Stage2 - PDF](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE2.pdf)
- [Stage3 - PNG](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE3.png)
- [Stage3 - PDF](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE3.pdf)
- [Stage4 - PNG](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE4.png)
- [Stage4 - PDF](https://github.com/yyhao0422/Implementing-a-simple-WEBIDF-App/blob/master/images/ARCHITECTURE-STAGE4.pdf)

# Learning From Cantrill 

[Cantrill - AWS Solution Architect Professional Course](https://learn.cantrill.io/courses/enrolled/895720)


