# Email-Newsletter
<img width="300" height="308" alt="image" src="https://github.com/user-attachments/assets/fe402bac-5357-4476-99c7-5ad1ae03ac4d" />

### This project is an Email Newsletter that utilizes Route53, S3, SES, Eventbridge, Lambda and IAM.
* Route53 was used to host the "Send From" domain/email of the newsletter.
* S3 was used to store the contact_list.csv file which contains recipient data. and the HTML Email Template used for formatting the newsletter content.
* SES & Lambda was used to send the email
* Eventbridge was used to schedule the newsletter
* IAM was used to give Lambda the permission to access S3 and SES


### S3 Bucket Contents
<img width="900" height="550" alt="Screenshot 2025-07-24 110539" src="https://github.com/user-attachments/assets/59f97785-1f79-4ab6-804d-cfd08f5139ee" />

### Successfully tested Lambda function
<img width="900" height="550" alt="Screenshot 2025-07-24 110501" src="https://github.com/user-attachments/assets/07a8bf97-f669-40e3-a9b4-41a042e919a2" />

### Scheduling Eventbridge 
<img width="900" height="550" alt="image" src="https://github.com/user-attachments/assets/d4c8c55b-b83b-4730-8f8d-2413b490387b" />

### Newsletter successfully arrived in email
<img width="900" height="550" alt="Screenshot 2025-07-24 111130" src="https://github.com/user-attachments/assets/95ba0c46-d3d4-4091-9d81-0748c7f8916e" />
___________________________________________________________________________________________________________________________________________________________








