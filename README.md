                                  Automated Receipt Processing And Summarizing Tool
                                  
  This project helps you build an automated receipt processing system using AWS services like S3, Textract, DynamoDB, SES, and Lambda — all within the AWS Free Tier.
  
🚀 Tech Stack
AWS S3 – Storage for receipt uploads

Amazon Textract – Extract text from images

DynamoDB – Store receipt details

AWS SES – Email receipt summaries

AWS Lambda (Python 3.9) – Glue everything together

![image](https://github.com/user-attachments/assets/55458cd7-822d-46cf-8e0d-b46f10a32572)


                                    BackGround Action in DynamoDB

  ![Output Receipts Duration](https://github.com/user-attachments/assets/1031b125-147c-41c6-b35d-b1b447de6dba)


                                    Output of Email Received
                                    
The summary is sent to registered email using the Amazon SES which summarize the Receipt automatically.

![Email Summary](https://github.com/user-attachments/assets/2b08da38-19fd-4995-91e3-fdcac025e0ac)

