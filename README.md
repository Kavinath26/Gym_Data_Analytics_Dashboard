# Gym Membership Real-Time Analytics

A full-stack project that integrates **web development, database management, and real-time analytics** to manage gym membership registrations and provide actionable insights through interactive dashboards.

---

## 📌 Project Overview
The **Gym Membership Real-Time Analytics** is a complete system that:
- Collects **gym membership registrations** via a Flask web application.
- Stores user details, subscription type, and pricing information in a **MySQL database**.
- Applies **business logic** such as automated pricing and student discounts.
- Connects the database to **Power BI via MariaDB ODBC** for **real-time data visualization**.
- Provides insights into **registrations, revenue trends, demographics, and membership distribution**.

This project demonstrates **end-to-end data handling**, from **data collection → storage → processing → visualization → insights**.

---

## 🚀 Features
- ✅ Web-based **gym registration form** with subscription plans.  
- ✅ **Automated pricing logic** with student discounts.  
- ✅ Data stored securely in **MySQL database**.  
- ✅ **Flask backend API** for form handling and database operations.  
- ✅ **Power BI dashboards** connected via MariaDB ODBC for **real-time visualization**.  
- ✅ Insights into revenue, subscription trends, and demographics.  

---

## 🛠️ Tools & Technologies Used
**Backend & Database**
- Python (Flask Framework)  
- MySQL 
- SQLAlchemy (for DB operations)  

**Frontend**
- HTML, CSS, JavaScript  

**Data Analytics & Visualization**
- Power BI  
- MariaDB ODBC Connector  

**Other Tools**
- Git & GitHub (Version Control)  
- VS Code / PyCharm (IDE)  

---

## 📊 Dashboard Preview

**Example:**  

<img width="1285" height="724" alt="Screenshot 2025-08-23 040149" src="https://github.com/user-attachments/assets/2b7d2e9e-2913-433d-9187-00563626da6e" />

---
<img width="1919" height="1020" alt="Screenshot 2025-08-23 040842" src="https://github.com/user-attachments/assets/7b923157-59c3-4080-9be8-ddce949e16c1" />

---

## ⚙️ Project Architecture
1. **User Registration** → User fills gym membership form on the Flask web app.  
2. **Data Storage** → Submitted data is stored in **MySQL database**.  
3. **Data Pipeline** → MariaDB ODBC connector bridges the database with Power BI.  
4. **Visualization** → Power BI dashboards provide real-time analytics.  
5. **Insights** → Managers can track revenue, memberships, and demographics.  

---

## 📈 Insights Generated
- Distribution of **subscription plans** (Basic, Standard, Premium).  
- **Revenue analysis** based on memberships.  
- **Student vs Non-Student membership ratio**.  
- **Demographic insights** for better decision-making.  

---

## 🖥️ How to Run the Project Locally
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Gym-Data-Analytics-Dashboard.git
   cd Gym-Data-Analytics-Dashboard
2. **Set up virtual environment and install dependencies**
   ```bash
   pip install -r requirements.txt
3. **Start MySQL server and create database:**
   ```bash
   CREATE DATABASE gym_db;
4. **Configure database credentials in app.py:**
   ```bash
   app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql+pymysql://username:password@localhost/gym_db'
5. **Run the Flask application**
   ```bash
   python app.py
6. **Connect Power BI to MariaDB (using ODBC) for real-time dashboards**

## 🎯 Key Learning Outcomes

- Building a full-stack application with Flask and MySQL.
- Implementing business logic for subscription pricing.
- Creating real-time analytics dashboards with Power BI.
- Designing an end-to-end data pipeline from collection to visualization.
- Enhancing data-driven decision-making using interactive insights.
