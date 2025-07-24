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
<img width="900" height="550" alt="sendmonthly" src="https://github.com/user-attachments/assets/e53b6740-0e8d-4b0a-86b1-c714a8d33032" />

### Newsletter successfully arrived in email
<img width="900" height="550" alt="Screenshot 2025-07-24 111130" src="https://github.com/user-attachments/assets/95ba0c46-d3d4-4091-9d81-0748c7f8916e" />
___________________________________________________________________________________________________________________________________________________________

<img width="1000" height="550" alt="Screenshot 2025-07-24 110539" src="https://github.com/user-attachments/assets/59f97785-1f79-4ab6-804d-cfd08f5139ee" />
<img width="1753" height="678" alt="Screenshot 2025-07-24 110501" src="https://github.com/user-attachments/assets/07a8bf97-f669-40e3-a9b4-41a042e919a2" />
<img width="1460" height="650" alt="Screenshot 2025-07-24 110240" src="https://github.com/user-attachments/assets/733df8da-a9ee-42aa-a80b-8ee926eaab26" />
<img width="1433" height="781" alt="Screenshot 2025-07-24 111130" src="https://github.com/user-attachments/assets/95ba0c46-d3d4-4091-9d81-0748c7f8916e" />






