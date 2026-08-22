## 1. Local → EC2 (Upload)

\- open poweerrshell and fire command

\- scp -i mykey.pem index.html ec2-user@YOUR_EC2_IP:/home/ec2-user/

## 2. Folder Upload

-\ scp -i mykey.pem -r website/ ec2-user@your-ec2-ip:/home/ec2-user

## 3. EC2 Local Download

\- scp -i mykey.pem ec2-user@YOUR_EC@_IP:/home/ec2-user/website/ .
