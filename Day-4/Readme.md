# 🔐 What is a Security Group in AWS?
- A Security Group (SG) acts like a virtual firewall for your EC2 instance.

- 🧠 In Simple Words: A Security Group controls who can connect to your server and on which ports (like SSH on port 22, HTTP on port 80).

# ✅ Key Features of Security Groups:
- Attached to EC2 Instances
- Only allows allow rules (no deny)
- Stateful — if you allow incoming traffic, the response goes out automatically
- Default: Denies all traffic

# 🛡️ What is a NACL (Network Access Control List)?
A Network ACL is another type of firewall that works at the subnet level, not at the instance level.

- 🧠 In Simple Words: A NACL is like a gate for the whole neighborhood (subnet), while a security group is like a door for your house (EC2).

# ✅ Key Features of NACLs:
- Attached to subnets
- Supports Allow and Deny rules
- Stateless — you must define both inbound and outbound rules
- Default: Allows all traffic

🧠 Final Example to Understand:
Imagine:

🏠 EC2 = your house

🚪 Security Group = your front door (who can come in)

🏘️ Subnet = your neighborhood

🚧 NACL = the security gate at the entrance
