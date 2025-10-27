## 📖 Overview

This repository provides a **step-by-step guide** to help you configure **Microsoft SQL Server** and connect it to **Node.js** on **Windows** using **SQL Server Management Studio (SSMS)**.

Whether you're building APIs, dashboards, or enterprise applications, this guide will walk you through everything you need — from installation to database connection testing.

---

## 🎯 What You'll Learn
- How to **install and configure Microsoft SQL Server** and **SQL Server Management Studio (SSMS)**
- How to **enable authentication** and **network protocols** for Node.js access
- How to **install the `mssql` package** and connect Node.js to your database
- How to **run test queries** and troubleshoot common connection issues

---

## 🧠 Why This Repo
Most tutorials skip important configuration steps — especially around **SQL authentication**, **TCP/IP setup**, or **firewall rules**.  
This guide covers every step carefully so you can:
- Avoid “login failed” and connection timeout errors  
- Get a working **Node.js–SQL Server setup** within minutes  
- Learn how to configure **secure and stable** connections for production environments  

---

## ⚙️ Technologies Used
- **Node.js**
- **Microsoft SQL Server (Express or Developer edition)**
- **SQL Server Management Studio (SSMS)**
- **Windows 10 or later**
- **npm `mssql` driver**

---

## ⚙️ Step 1 — Install SQL Server and SSMS
1. Download **SQL Server** from [Microsoft’s official page](https://www.microsoft.com/en-us/sql-server/sql-server-downloads).
2. Install **SQL Server Management Studio (SSMS)**.
3. Open SSMS and connect to your local server.
4. Enable SQL authentication and set a strong password for the `sa` user.

---

## 🔌 Step 2 — Configure Network and Authentication
- Enable TCP/IP in **SQL Server Configuration Manager**.
- Restart the SQL Server service.
- Make sure your firewall allows connections on port **1433**.

---

## 🧩 Step 3 — Install Node.js and MSSQL Driver
```bash
npm init -y
npm install mssql

## 🏷️ Keywords
`nodejs` `mssql` `sql-server` `windows` `ssms` `database` `backend` `configuration`
