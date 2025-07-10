# HomePage-with-NetBeans

# Java MySQL Login App

A simple Java Swing application created in NetBeans that connects to a MySQL database and displays a basic homepage with navigation buttons.

---

## ✅ Features

- Connects to MySQL using JDBC
- Homepage with:
  - Welcome title
  - User greeting
  - Buttons: View Profile, Settings, Logout
- Clean layout using GroupLayout

---

## 🛠 Tools Used

- Java (JDK 8 or higher)
- NetBeans IDE
- MySQL (via XAMPP)
- JDBC Connector/J (.jar)
- Swing GUI

---

## 🚀 How to Run

1. **Start MySQL** using XAMPP
2. **Create a database** in phpMyAdmin (e.g., `loginformdb`)
3. Open `DatabaseConnection.java` and update:
   ```java
   private static final String URL = "jdbc:mysql://localhost:3306/loginformdb?useSSL=false&allowPublicKeyRetrieval=true";
   private static final String USER = "root";
   private static final String PASSWORD = "";
   ```
4. Add the MySQL connector `.jar` file to your project:
   - Right-click **Libraries** → **Add JAR/Folder**
   - Select the downloaded `mysql-connector-java-x.x.xx.jar`
5. Run `DatabaseConnection.java` to test the connection
6. Run `Homepage.java` to launch the UI

---

## 📁 Project Structure

```
YourProjectName/
├── nbproject/
├── src/
│   ├── DatabaseConnection.java
│   └── Homepage.java
├── build.xml
└── README.md
```

---

## 💡 Notes

- Default XAMPP MySQL credentials:
  - Username: `root`
  - Password: *(empty)*
- Ensure MySQL is running before launching the app
- You can extend the app by creating Profile and Settings pages linked from the homepage

---

