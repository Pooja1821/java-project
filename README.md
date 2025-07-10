# java-project
# 🔐 Security Management System

हा एक Java आधारित फाईल-हँडलिंग प्रोजेक्ट आहे, जो विद्यार्थ्यांची माहिती तपासून त्यांचा प्रवेश लॉग करतो.

 Maven Folder Structure:

SecurityManagementSystem/
│
├── pom.xml
└── src/
    └── main/
        └── java/
            └── packs/
                └── SecuritySystem.java

-------------------------------------------------------------------------------
                (Maven configuration file):

                <project xmlns="http://maven.apache.org/POM/4.0.0" 
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 
         http://maven.apache.org/xsd/maven-4.0.0.xsd">
         
    <modelVersion>4.0.0</modelVersion>

    <groupId>com.pooja</groupId>
    <artifactId>SecurityManagementSystem</artifactId>
    <version>1.0-SNAPSHOT</version>

    <properties>
        <maven.compiler.source>17</maven.compiler.source> <!-- Or use 1.8/11 -->
        <maven.compiler.target>17</maven.compiler.target>
    </properties>

</project>

-------------------------------------------------------------------------


## 📌 Project Features:

- ✅ Approved students list वरून तपासणी
- 🧾 Entry logs मध्ये date-time सह नोंद
- 🔍 Name आणि Roll No. वरून search करता येते
- 💾 सर्व माहिती फाईलमध्ये साठवते (No database)

-------------------------------------------------

## 🗂️ Project Structure:

SecurityManagementSystem/
│
├── approved_students.txt 
├── entrylog.txt
├── SecuritySystem.java 
├── output.png 
└── README.md 

----------------------------------------------



## 🖥️ Sample Output:


=== Security Management System ===
1. Verify and Allow Entry
2. Add Approved Student
3. View Entry Logs
4. Search Entry by Name or Roll
5. Exit
Enter your choice: 1

Enter Name: Priya
Enter Roll Number: 102
Enter Branch: IT

✅ Entry allowed and logged.
--------------------------------------------------------


🧠 Technologies Used:

Java

IntelliJ IDEA

File I/O (BufferedReader, BufferedWriter)

SimpleDateFormat
-----------------------------------------------------
Created by: Pooja1821 👩‍💻
Language: 🇮🇳 Marathi + English
Date: July 2025

