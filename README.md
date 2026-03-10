# Task 6 – DevOps

## AWS VPC and EC2 Setup

---

## 📌 Task Description

Create a Virtual Private Cloud (VPC) with an Internet Gateway, configure networking components such as public and private subnets, and launch a Linux EC2 instance using the public subnet.

---

## 🛠 Technologies Used

* AWS VPC
* AWS EC2

---

## ⚙️ Steps Performed

1. Created a **VPC** in AWS.
2. Created and attached an **Internet Gateway** to the VPC.
3. Created a **Public Subnet** and **Private Subnet**.
4. Created a **Route Table** and added a route to the Internet Gateway.
5. Associated the **Public Subnet** with the route table.
6. Launched a **Linux EC2 instance** inside the public subnet.
7. Verified the instance details and networking configuration.

---

## 📸 Screenshots

### EC2 Instance Running

![EC2 Running](screenshots/EC2 Instance Running.png)

### EC2 Public IP Address

![Public IP](screenshots/02_EC2_Public_IP.png)

### EC2 VPC and Subnet Details

![VPC Subnet](screenshots/03_EC2_VPC_Subnet_Details.png)

### EC2 Instance Configuration

![Instance Details](screenshots/04_EC2_Instance_Details.png)

### EC2 Launch Information

![Launch Details](screenshots/05_EC2_Launch_Details.png)

---

## ✅ Result

The Linux EC2 instance was successfully launched inside the configured VPC and public subnet.
The instance received a public IP and is connected to the internet through the Internet Gateway.

---

## 📚 Author

Dusyaant
DevOps Task Submission
