# SQLMap - SQL Injection Demonstration

This project showcases a practical example of SQL Injection using `sqlmap` against a deliberately vulnerable web app for educational purposes.

## 💻 Tools Used

- **sqlmap v1.5.5#stable**
- Linux Terminal
- Microsoft SQL Server as backend
- Test URL: `http://<example>/lab.aspx?branch_id=7` *(for educational use only)*

## ⚠️ Disclaimer

> This project is created for ethical hacking practice on authorized or test environments only. Never attempt to attack systems without explicit permission.

## 🧪 Demo

### 🔍 Detection and Database Discovery

![WAF Warning & DB Discovery](Screenshot_2025-07-06_21-41-34.png)

### 📊 Table Enumeration in `msdb`

![Table Dump](Screenshot_2025-07-06_21-42-47.png)

## 📁 Files

- SQLMap command used:
  ```bash
  sudo sqlmap -u "http://<example>/lab.aspx?branch_id=7" --tables
