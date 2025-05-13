# Hospital Management System

A comprehensive Java-based Hospital Management System developed using modern web technologies and enterprise standards. This system covers a wide range of healthcare management functionalities including patient registration, staff management, pharmacy handling, and report generation.

---

## 🔧 Technologies Used

- **Java (JSP & Servlets)** – Backend development
- **Hibernate ORM** – Database interaction
- **Oracle Database** – Data storage and management
- **Jasper Reports** – Report generation
- **Design Patterns** – For scalable and maintainable architecture
- **Maven** – Project and dependency management

---

## 📦 Prerequisites & Installation

1. Install **Java JDK/JRE** and **Maven** on your system.
2. Clone or download the project repository.
3. Import the project into **Eclipse** or **NetBeans**.
4. Right-click the project → `Run As` → `Maven install`
5. Clean and build the project.
6. Deploy the generated WAR file to a compatible Java server (e.g., **Tomcat**, **JBoss**).

### To Run the Application:

- Configure your server (Tomcat/JBoss)
- Deploy the application
- Start the server (`start.bat` for Windows or `start.sh` for Linux)

---

## 📱 Screenshots

### Home Page

![home](https://user-images.githubusercontent.com/11550708/27002545-accfd84e-4d99-11e7-9252-3ca14829f4b4.PNG)

### Mobile View

![mobileview2](https://user-images.githubusercontent.com/11550708/27002547-aced4104-4d99-11e7-86b2-cad04e5c0d47.PNG)

### Mail Functionality

![viewallsentmails](https://user-images.githubusercontent.com/11550708/27002543-acb02832-4d99-11e7-9772-3dbf3d094872.PNG)  
![compose](https://user-images.githubusercontent.com/11550708/27002555-ad34d654-4d99-11e7-81d8-11f8f1b335bf.PNG)

### Statistics & Reports

![statisticpage](https://user-images.githubusercontent.com/11550708/27002556-ad53f408-4d99-11e7-8a32-8e6adc9398ca.PNG)  
![druginvoice](https://user-images.githubusercontent.com/11550708/27002557-ad891e8a-4d99-11e7-8651-324a25fe8fd3.PNG)  
![employeereport](https://user-images.githubusercontent.com/11550708/27002549-ad0e75a4-4d99-11e7-9226-8e1372e9a679.PNG)

### Profile & Pharmacy

![profileview](https://user-images.githubusercontent.com/11550708/27002553-ad3017d6-4d99-11e7-8e4e-a00179f71850.PNG)  
![pharmacy](https://user-images.githubusercontent.com/11550708/27002550-ad0ec4c8-4d99-11e7-95ac-fa8e9008a335.PNG)  
![selldrug](https://user-images.githubusercontent.com/11550708/27002554-ad317e1e-4d99-11e7-8776-d4f55758286e.PNG)

### Patient Management

![bookbed](https://user-images.githubusercontent.com/11550708/27002544-acb60e64-4d99-11e7-8e3f-ffdd88afd3de.PNG)  
![patient](https://user-images.githubusercontent.com/11550708/27002548-acf6d480-4d99-11e7-812d-1d82413682c8.PNG)

### Password Management

![changepassword](https://user-images.githubusercontent.com/11550708/27002551-ad11112e-4d99-11e7-9f34-33a6c061ad3e.PNG)

---

## 🚀 Deployment Guide

- Clean and build the project using Maven.
- Deploy the WAR file:
  - **Tomcat** → place in the `webapps` folder
  - **JBoss** → place in the `standalone/deployments` folder
- Run the appropriate startup script based on your OS:
  - Windows: `start.bat`
  - Linux: `start.sh`

---

## 📌 Notes

- Ensure Oracle Database is up and configured.
- Modify database connection settings in Hibernate configuration as per your setup.
