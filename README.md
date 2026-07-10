# CrisisNet — Disaster & Emergency Alert Management System

A full-stack Java web application for managing disaster and emergency alerts 
in real time, built using JSP, Servlets, and MySQL following the MVC 
(Model-View-Controller) architectural pattern.

## What it does
- Secure session-based login module for emergency response officers
- Real-time command dashboard with live statistics (active, monitoring, 
  resolved alerts, total affected)
- Full CRUD (Create, Read, Update, Delete) operations for managing 
  disaster alerts
- Search and filter alerts by disaster type, status, and keyword
- Color-coded severity and status badges with disaster-type icons for 
  quick visual assessment
- Status lifecycle tracking (Active → Monitoring → Resolved)

## Tech Stack
- **Frontend:** JSP (JavaServer Pages), Bootstrap 5, Google Fonts
- **Backend:** Java Servlets, MVC Architecture
- **Database:** MySQL, JDBC with DAO design pattern
- **Server:** Apache Tomcat 10.1
- **IDE:** Eclipse IDE for Enterprise Java

## Project Structure
- `src/main/java` — Servlets, DAO classes, and model classes
- `src/main/webapp` — JSP pages (login, dashboard, alert forms, alert details)

## How to Run
1. Extract the project ZIP file
2. Import the project into Eclipse IDE as a Maven/Dynamic Web Project
3. Set up a MySQL database and configure connection details in DBConnection.java
4. Deploy the project on Apache Tomcat 10.1
5. Access via localhost in your browser

## Author
Monitha S — B.Tech CSE (Data Science), Presidency University, Bengaluru
