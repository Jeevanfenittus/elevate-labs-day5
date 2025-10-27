# Cloud Database Lab – AWS RDS MySQL


This lab covers:
- Creating an AWS RDS MySQL instance
- Configuring access and security
- Performing SQL operations (CREATE, INSERT, SELECT)
- Optional Python connectivity



 Steps Performed

1️⃣ Create an RDS MySQL Instance
- Go to AWS Console → RDS → Databases → Create database
- Engine: MySQL
- Free Tier: Yes
- Username: `admin`  
- Password: `YourPassword123`  
- Region: `eu-north-1` (example)  



2️⃣ Configure Access
- Enabled **public access**  
- Added your local IP to the **authorized network**  
- Noted the **endpoint** for connection

 3️⃣ Connect to the Database
- Using MySQL Workbench / DBeaver:
