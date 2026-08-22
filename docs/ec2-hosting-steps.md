## Host website in AWS EC2 seerver
## 1 Creat EC2 Instance 
\- - Creat AWS account

\- - Launch Instance

\- - Select Amazon Linux

\- - Select Instance type

\- - Key pair create/download

\- - Security Group :
\- 1.SSH → 22
\- 2.HTTP → 80
\- 3.HTTPS → 443

## 2 EC2 se SSH connect karo

\- ssh -i mykey.pem ec2-user@YOUR_EC2_PUBLIC_IP

## 3 Server update 

\- sudo dnf update -y

## 4 Install web server

\- sudo dnf install nginx -y

## 5 Start nginx

\- sudo dnf install nginx -y

## 6 Check nginx status

\- sudo systemctl status nginx

## 7 Upload website file

\- cd /usr/share/nginx/html

\- sudo nano index.html

## 8 Check website

\- http://YOUR_EC2_PUBLIC_IP 
