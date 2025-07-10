# HomePage-with-NetBeans

# Java MySQL Login App

This is a simple Java Swing application created using NetBeans that connects to a MySQL database and displays a basic homepage GUI with navigation buttons.

## ✅ Features
- MySQL database connection using JDBC
- Homepage with welcome message and navigation buttons (View Profile, Settings, Logout)
- Clean layout using GroupLayout

## 🛠️ Tools Used
- Java (JDK 8+)
- NetBeans IDE
- MySQL (via XAMPP)
- JDBC Connector/J
- Swing GUI components

## 🚀 How to Run

1. **Start MySQL** using XAMPP
2. **Create a database** in phpMyAdmin (e.g., `loginformdb`)
3. In `DatabaseConnection.java`, update:
   ```java
   private static final String URL = "jdbc:mysql://localhost:3306/loginformdb?useSSL=false&allowPublicKeyRetrieval=true";
   private static final String USER = "root";
   private static final String PASSWORD = "";
4.Add the MySQL Connector .jar to your project:
    Right-click Libraries > Add JAR/Folder
    Select mysql-connector-java-<version>.jar
5.Run DatabaseConnection.java to test connection
6.Run Homepage.java to open the UI
