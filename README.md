## Flask-Based User Authentication System

### **Project Overview**
This project is a basic **web-based authentication system** that allows users to **register, log in, and view their personal details**. The system uses **Flask for backend processing, SQLite for storage**, and can be **deployed on AWS** for cloud accessibility.

### **Features**
✅ **User Registration** – Users can create an account with a **username, password, and personal details**  
✅ **Login System** – Users can log in with their credentials to access their profile  
✅ **Profile Retrieval** – Displays **first name, last name, and email** after successful authentication  
✅ **Simple UI** – HTML-based registration and login pages  
✅ **AWS Deployable** – Can be deployed on an **EC2 instance with Apache & WSGI**  

---

### **Tech Stack**
- **Backend:** Flask (Python)
- **Database:** SQLite (Can be upgraded to AWS RDS)
- **Frontend:** HTML & Basic Forms
- **Deployment:** AWS EC2 (Ubuntu/ Amazon Linux) + Apache WSGI

---

### **Installation & Setup**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/yourusername/auth-system.git
   cd auth-system
   ```

2. **Install Dependencies**  
   ```bash
   pip install flask
   ```

3. **Run the Flask App**  
   ```bash
   python app.py
   ```

4. **Access the Web App:**  
   Open `http://127.0.0.1:5000/` in your browser.

---

### **AWS Deployment Steps**
1. **Launch an AWS EC2 Instance** (Ubuntu/ Amazon Linux)
2. **Install Required Packages**
   ```bash
   sudo yum update -y
   sudo yum install python3-pip
   pip3 install flask sqlite3
   ```
3. **Deploy using Apache & WSGI**
   - Configure **Apache HTTP Server** for serving Flask
   - Use a **reverse proxy** to route traffic

4. **Upgrade Database (Optional)**
   - Connect Flask to **AWS RDS PostgreSQL/MySQL** instead of SQLite.

---

### **Security Improvements**
🔒 **Hash Passwords** – Use `bcrypt` for password encryption  
🔒 **CSRF Protection** – Implement **CSRF tokens** for form validation  
🔒 **Secure Database** – Move from **SQLite to AWS RDS**  
🔒 **HTTPS Support** – Deploy using **AWS Load Balancer & SSL**  

---

### **Contributing**
Feel free to **open issues, suggest improvements, or contribute new features** by submitting a pull request.

📩 **For questions or collaboration, reach out at:** your.email@example.com  

---

### **License**
📜 This project is licensed under the **MIT License**.

---

🚀 **Ready to deploy? Take it to AWS and build something amazing!** 🎉
