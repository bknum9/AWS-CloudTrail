# AWS-CloudTrail
<h2>Creating a CloudTrail Trail and EventBridge Alert for Console Sign-Ins</h2>
<img width="1438" alt="CT1" src="https://github.com/user-attachments/assets/013f2b7c-2709-4bb5-b38a-76fc469b096f">
1. Created trail in CloudTrail to be encrypted and saved in s3 bucket to log sign in attempts for root user
<img width="1438" alt="CT2" src="https://github.com/user-attachments/assets/4521881f-2a8e-42e0-9be8-891f941039fd">
2. Creating SNS topic with an email subscription
<img width="1438" alt="CT3" src="https://github.com/user-attachments/assets/cd7ac408-59be-427a-bffd-e3b9036d06df">
3. Creating EventBridge rule to send an email to the subscribed email via SNS for sign in alerts
