💻 What is EC2?
EC2 (Elastic Compute Cloud) is an AWS service that lets you run virtual servers (called instances) in the cloud.


🧠 In Simple Words:
EC2 is like renting a computer from Amazon that lives in a data center.
You can use it to run websites, apps, software, or anything you’d normally do on your own computer — but it’s on the internet.

💻 Why Do We Use EC2?
💪 Run applications	: You can run websites, backend APIs, machine learning models, etc.

🧑‍💻 No need to buy hardware	You don’t need to buy servers — just rent and pay only for what you use

🌍 Accessible globally	You can access your EC2 from anywhere in the world.

⚙️ Highly customizable	Choose the amount of CPU, RAM, storage, and OS (Linux, Windows, etc.).

📈 Scalable	Start small and increase power anytime if your traffic grows. 

🔧 What Can You Do with an EC2 Instance?
Host a website or web application

Run a backend server for a mobile app

Set up a database server

Run DevOps tools like Jenkins, Docker, Kubernetes

Perform data analysis or run ML models

Use it for practice/labs in AWS

🚀 How to Create an EC2 Instance (Step-by-Step)
🧭 Step-by-Step:
1. 🔐 Login to AWS Console
Go to https://console.aws.amazon.com

Sign in with your AWS credentials.

2. 🔎 Search for EC2
In the search bar at the top, type “EC2” and click on EC2 service.

3. 🟢 Launch Instance
Click on the "Launch instance" button.

4. 📝 Configure the Instance
Here’s what you’ll see and need to choose:

Field	What to Select
Name	Any name (e.g., MyFirstEC2)
Amazon Machine Image (AMI)	Choose Amazon Linux 2023 or Ubuntu
Instance Type	Choose t2.micro (Free Tier eligible)
Key Pair (login)	Select an existing key pair OR create a new one (save it!)
Network Settings	Keep default; allow SSH (port 22) and HTTP (port 80) if hosting a website
Storage	8 GB (default) is enough
Advanced settings	Leave it as is

5. ✅ Click "Launch Instance"
Wait for a few seconds.

You’ll see a message saying "Your instance is launching!"

6. 🖥️ Connect to EC2 (Using SSH)
If you chose a Linux AMI:

Go to EC2 Dashboard > Instances.

Select your instance and click Connect.

Choose the SSH client tab.

Copy the command given (looks like this):
ssh -i "your-key.pem" ec2-user@your-ec2-public-ip
Run this command in your terminal (Linux/macOS) or Git Bash (Windows).

✅ You’re now logged into your cloud server!