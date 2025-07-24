# Email-Newsletter
<img width="300" height="308" alt="image" src="https://github.com/user-attachments/assets/fe402bac-5357-4476-99c7-5ad1ae03ac4d" />

### This project is an Email Newsletter that utilizes Route53, S3, SES, Eventbridge, Lambda and IAM.
* Route53 was used to host the "Send From" domain/email of the newsletter.
* S3 was used to store the contact_list.csv file which contains recipient data. and the HTML Email Template used for formatting the newsletter content.
* SES & Lambda was used to send the email
* Eventbridge was used to schedule the newsletter
* IAM was used to give Lambda the permission to access S3 and SES


