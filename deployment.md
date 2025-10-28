# ✅ Deployment Steps - AWS EC2 Website Hosting

1️⃣ Launched EC2 instance (Amazon Linux 2, t2.micro)
2️⃣ Enabled Security Group rules:
   - SSH (22)
   - HTTP (80) - Anywhere
3️⃣ Connected using EC2 Instance Connect
4️⃣ Installed Apache:
   sudo yum install httpd -y
   sudo systemctl start httpd
   sudo systemctl enable httpd
5️⃣ Deployed website:
   sudo nano /var/www/html/index.html
6️⃣ Verified website using Public IP
7️⃣ Collected screenshots and uploaded to GitHub
