# 🛡️ SOC-Kali-Logs

Access and monitor **Kali Linux logs** remotely using **PuTTY**

---

## 📘 Project Overview

This lab demonstrates how to access and view **system logs from a Kali Linux machine** remotely using **PuTTY** on Windows.
It’s a simple yet effective setup for understanding remote connections and log monitoring — an essential skill for anyone learning **SOC (Security Operations Center)** practices.

---

## ⚙️ Steps to Set Up

### **Step 1: Get the Kali Linux IP Address**

1. Open the **terminal** in Kali Linux.
2. Run the command `ifconfig`.
3. Note down the **IP address** of your Kali system.

---

### **Step 2: Open PuTTY on Windows**

1. Launch **PuTTY** on your Windows system.
2. In the **Host Name (or IP address)** field, enter the IP address you noted from Kali.
3. Click **Open** to start the SSH session.

---

### **Step 3: Handle the Security Alert**

* When the **PuTTY Security Alert** window appears, click **Accept** to proceed with the connection.

---

### **Step 4: Login to Kali Linux**

* Enter your **username** and **password** when prompted to establish a secure connection.

---

### **Step 5: Access the Log Directory**

* Once connected, navigate to the log directory by running:
<img width="772" height="499" alt="Screenshot 2025-10-19 174230" src="https://github.com/user-attachments/assets/d4c54512-6df1-4a30-9a3b-95396c75a58d" />

  ```
  cd /var/log
  ```
* You can now explore and analyze system log files directly from your Windows system through PuTTY.

---

## 🎯 Outcome

You have successfully created a **SOC Lab environment** where you can securely access and analyze **Kali Linux logs** remotely using PuTTY — a fundamental step toward building real-world SOC analysis skills.

