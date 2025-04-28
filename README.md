## Objective
Use AWS S3 to host a static website and manage object storage using AWS CLI.

## Steps  
## S3 Bucket Created
- Name: 'misolamaceproject'
- Region: 'us-east-1'
   ![image](https://github.com/user-attachments/assets/50cbac52-271e-4304-81cb-43d4087324a0)
  
## Basic Object Operations
 Uploaded, retrieved, and deleted 'test-txt'
 ![image](https://github.com/user-attachments/assets/736382a7-c6c3-4d42-8e4b-4ecbd3d4ed02)
 ![image](https://github.com/user-attachments/assets/c73481f5-08f7-4c74-b230-f590be551a5f)

Opened the CLI to interact with my Bucket through Terminal and used some of the commands below:
   1. AWS S3 ls - to list out the items in my bucket
   2. aws s3 cp test.txt s3://misolamaceproject/
   3. aws s3 cp s3://misolamaceproject/test.txt
   4. aws s3 rm s3://misolamaceproject/test.txt

## Public Access Configuration
- Applied public-read ACL
- Added bucket policy
- Enabled Static Website

 
## Website Hosting

- Mentee Name: Ada Patricia
- Project: HTML portfolio
- Hosted URL: http://misolamaceproject.s3-website-us-east-1.amazonaws.com/index.html




# Error encountered. 

1. I got an 'Access Denied' error message from my bucket, 
   
![image](https://github.com/user-attachments/assets/9b9b33b1-4f6c-4059-b88a-b317133ba298)
  
3. I had to edit my 'Bucket Policy' in JSON Format. This was resolved and my website went live. 

![image](https://github.com/user-attachments/assets/18e23a27-7494-4d79-8031-43b485e3a858)

![image](https://github.com/user-attachments/assets/eb6b3b29-ab35-488c-b3e8-7c6ffb566f3a)


