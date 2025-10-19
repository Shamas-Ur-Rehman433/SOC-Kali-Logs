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
<img width="861" height="541" alt="Screenshot 2025-10-19 180921" src="https://github.com/user-attachments/assets/0fbc527a-a850-4e91-a640-33bca07cc1c2" />

---

### **Step 2: Open PuTTY on Windows**

1. Launch **PuTTY** on your Windows system.
2. In the **Host Name (or IP address)** field, enter the IP address you noted from Kali.
3. Click **Open** to start the SSH session.
<img width="772" height="499" alt="Screenshot 2025-10-19 174230" src="https://github.com/user-attachments/assets/c48c5238-a680-4437-9a22-0a1caa35a72b" />

---

### **Step 3: Handle the Security Alert**

* When the **PuTTY Security Alert** window appears, click **Accept** to proceed with the connection.
<img width="854" height="416" alt="Screenshot 2025-10-19 174430" src="https://github.com/user-attachments/assets/6a60168d-6492-420c-bfe8-ed3e6cba1ad6" />

---

### **Step 4: Login to Kali Linux**

* Enter your **username** and **password** when prompted to establish a secure connection.
<img width="1100" height="719" alt="Screenshot 2025-10-19 174733" src="https://github.com/user-attachments/assets/d5ba070c-7768-4047-a57c-26f3a473dd00" />

---

### **Step 5: Access the Log Directory**

* Once connected, navigate to the log directory by running:
<img width="1100" height="719" alt="Screenshot 2025-10-19 174733" src="https://github.com/user-attachments/assets/d5ba070c-7768-4047-a57c-26f3a473dd00" />

  ```
  cd /var/log
  ```
* You can now explore and analyze system log files directly from your Windows system through PuTTY.

---

## 🎯 Outcome

You have successfully created a **SOC Lab environment** where you can securely access and analyze **Kali Linux logs** remotely using PuTTY — a fundamental step toward building real-world SOC analysis skills.

