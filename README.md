
# 🛢️ FAOS - Fuel Agency Operation Suite

FAOS is a full-stack Java web application that simplifies fuel agency operations like cylinder management, customer orders, and email alerts.  
Built with **Spring Boot**, **Thymeleaf**, and **MySQL**, it offers a clean UI and automated backend processing.

---

## 🛠️ Technologies Used

**Backend**:  
- Spring Boot  
- Spring Data JPA  
- MySQL  

**Frontend**:  
- Thymeleaf  
- HTML, CSS  

**Others**:  
- Spring Mail (Gmail SMTP)  

---

## 🔑 Features

- 👥 **Customer & Admin login** – Separate authentication for customers and admins  
- 🧮 **Cylinder Tracking** – Monitors availability/status (full, empty)  
- 📬 **Automatic Refill Notifications** – Admin gets email alerts when stock is low  
- 🛒 **Order Management** – Customers place orders, system updates inventory  
- 📧 **Email Notifications** – Alerts admin about low stock/system events  

---

## 📁 Project Structure

/src/main/java -> Java code (Controllers, Services, Models)
/src/main/resources/templates -> Thymeleaf HTML templates
/src/main/resources/application.properties -> DB & mail config

---

## 🚀 Getting Started

1. **Clone the repo**  
git clone https://github.com/harshithasure10/fuel-agency-operation-suite.git


2. **Create a MySQL database** named: fuelagencydb


3. **Configure your credentials** in application.properties:  
- MySQL DB URL, username, password  
- Gmail SMTP email and password  

4. **Run the Spring Boot application** from your IDE or using mvn spring-boot:run

---

## 📬 Email Notification Setup

This project uses **Gmail SMTP** to send emails.  

In application.properties, add:

spring.mail.username=your_email@gmail.com

spring.mail.password=your_gmail_app_password

Make sure 2-step verification is enabled on Gmail and generate an app password.

❤️ Thank you for checking out FAOS!
