# Sailpoint Installation Guide

## Introduction
This guide outlines the essential steps for installing and deploying SailPoint, with a focus on version 8.1. Follow these instructions carefully to ensure a smooth installation process.

## Installation Steps

### Step 1: Install Java and Set Environment Variables
Ensure that Java is installed on your system. Set the necessary environment variables to support SailPoint.

### Step 2: Install MySQL 8.0 Database
Install MySQL 8.0 on your system. This database is required for SailPoint to function correctly.

### Step 3: Install Apache Tomcat (Windows Installer)
If you're using the Windows installer, install Apache Tomcat on your system.

### Step 4: Extract IdentityIQ-8.1.zip Files
Download the IdentityIQ 8.1.zip file from [SailPoint Community](https://community.sailpoint.com/t5/IdentityIQ-Server-Software/IdentityIQ-8-1/ta-p/158175#toc-hId-1744926198). Extract the contents, and expand the identityiq.war file using the command: 
```bash
jar -xvf identityiq.war
```

### Step 5: Paste identityiq.war in Tomcat webapps Directory
Copy the extracted `identityiq.war` file and paste it into the following directory:
```bash
C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps
```

### Step 6: Create Database
Navigate to the database folder at:
```bash
C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\identityiq\WEB-INF\database
```
Execute the SQL file `create_identityiq_tables-8.1.mysql` to create the required database tables.

### Step 7: Open MySQL Command Line
Open the command prompt and access the MySQL command line.

### Step 8: Execute SQL Script
In the MySQL command line, type the following command to execute the SQL script:
```sql
source C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\identityiq\WEB-INF\database\create_identityiq_tables-8.1.mysql
```

Ensure that the database is created successfully without errors.

## Conclusion
Congratulations! You have completed the installation and deployment of SailPoint. Make sure to review the documentation for any additional configurations or updates. If you encounter any issues, refer to the SailPoint community for support.
