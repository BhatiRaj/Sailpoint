# Sailpoint
Basic of sailpoint


The installation and deployment process contains the following parts:

    • Install Java and set environment variables
    • Install MySQL 8.0 database
    • Install Apache Tomcat if window installer
    • Extraft the identityiq-8.1.zip Files and expand identityiq.war using cmd jar-xvf identityiq.war
    • Download file from here :- https://community.sailpoint.com/t5/IdentityIQ-Server-Software/IdentityIQ-8-1/ta-p/158175#toc-hId-1744926198

paste identityiq.war in C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps
extract identityiq.war at same place

now create database 
so we go to this location C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\identityiq\WEB-INF\database
and execute this file create_identityiq_tables-8.1

open cmd open mysql 
type 
source C:\Program Files\Apache Software Foundation\Tomcat 9.0\webapps\identityiq\WEB-INF\database\create_identityiq_tables-8.1.mysql

