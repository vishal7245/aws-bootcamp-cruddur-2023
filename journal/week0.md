# Week 0 — Billing and Architecture

# Going through the checkpoints

- Attended the W01 livestream, learned a alot about architecture and **iron triangle**, how sacrifices is made in buisnesses based on the requirements, Chris session was great first time heard about TOGAF and how **well architectured** system plays crucuial role for **scaling of organization**, andrew taught how to make **napkin designs**
- Gone through chirag special considerations video on how to check your bills and usage, how to check the consumption of your free tier. **Setted up billing preferences** on my aws account, **Created billing alarm, Created a budget for the aws bootcamp, Explored cost allocation tags.**
- Gone through ashish’s AWS oraganization’s and IAM tutorial, learned about cloud security goals and what a organization expects from us, **Setted up MFA**, Explored AWS organization and **created an organization structure, setted up cloudtrail, Created a IAM role, policies and user.**
- Gone through andrew’s ****Generate Credentials, AWS CLI, Budget and Billing Alarm via CLI video,**** skipped passed the budget and billing part as I already did that in chirag’s video. Setted up my offline gitpod environment, installed AWS cli in wrong directory, learned to uninstall it, then installed again in the correct directory. ******************************Setted up the AWS CLI for startup of workspace.******************************
![Screenshot 2023-02-18 191415](https://user-images.githubusercontent.com/95615776/219869281-a4c714b5-02fb-4267-bd17-125402e60ddc.png)

- Gone through the lucid’s chart diagram for logical design architecture of our app.(attached the screenshot below)
![WhatsApp Image 2023-02-18 at 19 05 46](https://user-images.githubusercontent.com/95615776/219868971-b7c79181-6d55-4b52-9a14-f1fbf15f6e90.jpg)

![image](https://user-images.githubusercontent.com/95615776/219869245-d659eba9-c1d8-45c0-bebc-325e05895f76.png)


- For hooking up Health Dashboard to SNS and send notification when there is a service health issue, I found this helpful doc by aws
https://docs.aws.amazon.com/health/latest/ug/cloudwatch-events-health.html
followed the steps and successfully created the rule.

![image](https://user-images.githubusercontent.com/95615776/219870575-c2af51a8-d312-4936-9de6-77c7a6db04fd.png)

