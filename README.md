**Java Installation**

**Version:** 1.8

**Set Environment Variables:**
- **Path:** C:\Program Files\Java\jdk1.8.0_191\bin
- **JRE_HOME:** C:\Program Files\Java\jre1.8.0_191
- **JAVA_HOME:** C:\Program Files\Java\jdk1.8.0_191

**How to Check Java Installation?**
Open the command prompt and execute the following commands one by one:
```bash
java -version
javac -version
```
*Note: If these commands return the Java version, then Java is successfully installed.*

---

**Database Installation**

**Version:** MySQL 5.7 or 5.8

**Set Path:**
- **Path:** C:\Program Files\MySQL\MySQLServer5.7\bin

**Open MySQL using Command Line:**
```bash
mysql -u <username> -p<password>
```

**Open MySQL using Workbench:**

---

**Server Installation**

**Version:** Apache Tomcat 8.9 or 9

**To Start Server:**
Navigate to the following directory:
```bash
apache-tomcat-9.0.56\bin
```
Open the command prompt in the same directory and run the following commands:
```bash
startup.bat   # To start the server
shutdown.bat  # To stop the server
```
*Note: Do not open two servers on the same machine.*

---

**SailPoint Installation**

**War File Deployment**
- Database Creation
- IIQ.properties File Update
- Start Server

**Login to SailPoint Web Application:**
- **URL:** [localhost:8080/identityiq](http://localhost:8080/identityiq)
- **Username/Password:** spadmin/admin
