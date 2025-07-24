# Email-Newsletter
This project is an Email Newsletter using Route53, S3, SES, Eventbridge, Lambda and IAM.
Route53 was used to host the "Send From" Email of the newsletter.
S3 was used to store the contact_list.csv file and the HTML Email Template.
SES & Lambda was used to send the email
Eventbridge was used to schedule the newsletter
IAM was used to give Lambda the permission to access S3 and SES
