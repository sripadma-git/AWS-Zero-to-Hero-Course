🌐 What is VPC in AWS?
VPC (Virtual Private Cloud) is like your own private network inside AWS.

🧠 In Simple Words:
A VPC is like your own data center inside the AWS cloud, where you can launch and control your EC2 instances, databases, and other services — with full control over networking and security.

✅ Why Do We Use VPC?
Because it lets you:

🔐 Control who can access your resources

🌐 Define IP address ranges, subnets, and routing

🛡️ Use firewalls (Security Groups & NACLs) for security

🚦 Set up private or public access to your instances

🧠 Isolate your apps, like dev/test/prod environments


VPC: 	Your private network in AWS.

Subnet :	A smaller part of your VPC (can be public or private).

Route Table: Tells traffic where to go (e.g., to internet or within the VPC).

Internet Gateway (IGW):	Allows resources in your VPC to connect to the internet.

NAT Gateway: Allows private subnets to access the internet securely.

Security Group:	Firewall for EC2 instances.

NACL :	Firewall for subnets.