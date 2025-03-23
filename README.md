# 🎬 **Cinema Management Web Application** 🎟️

## 🌟 Overview
This project is a simple **Cinema Web Application** developed using **Java Servlet** and follows the **MVC (Model-View-Controller)** architecture. The application is designed to **manage a cinema**, allowing administrators to **handle movies, customers, showtimes, and ticket bookings**. It also provides features for users to **search for movies, view showtimes, and book tickets**.

---

## 🚀 Features
### 🎥 **For Users:**
- 🎞️ **Browse Movies**: Display a list of available movies with details such as **title, genre, duration, description, and poster**.
- 🎟️ **Book Tickets**: Select **movies, showtimes, and seats** to book tickets online.
- 📜 **View Booking History**: Track **past and upcoming bookings**.
- 🔐 **User Authentication & Authorization**: Users can **register, log in, and manage their accounts**.

### 🛠️ **For Admin:**
- 🎬 **Movie Management**: **Add, update, and delete** movie records.
- 👥 **Customer Management**: **Add, update, and delete** customer records.
- ⏳ **Schedule Type Management**: **Add, update, and delete** schedule types.
- 📊 **Revenue Reports**: View and analyze **business performance and revenue statistics**.
- 🏆 **Admin Panel**: Manage **movies, users, and reservations** with **role-based access**.

---

## 🛠️ Technologies Used
- **Backend Framework**: 🖥️ Java Servlet, JSP, JDBC
- **Database**: 💾 SQLSever 2014
- **View Layer**: 🏗️ JSP (JavaServer Pages) for dynamic rendering of pages
- **Frontend**: 🎨 HTML, CSS, Bootstrap, JavaScript
- **Server**: 🌐 Apache Tomcat

---

## 🏁 Getting Started
To run this project locally, follow these steps:

### 📌 Prerequisites
- ☕ Java 8 or higher
- 💾 SQLServer
- 🚀 Apache Tomcat
- 🖥️ IDE (Eclipse, IntelliJ IDEA, NetBeans, etc.)

### ⚙️ Installation
1. **Clone the repository:**
   ```bash
   https://github.com/phanthoi1101/SystemMovie.git
   ```
2. **Set up the SqlSever database:**
   - Create a Sql database named `QLRapPhim` and import the provided SQL script.
   - Update `db.properties` in `src/main/resources/` with your database credentials.
3. **Build and deploy the project on Apache Tomcat.**
4. **Access the application via:** `http://localhost:8080/SystemMovie/`.

---

## 📂 Folder Structure
```
 cinema-management/
 ├── src/
 │   ├── controller/    # 🎯 Servlet controllers
 │   ├── dao/           # 📦 Data Access Object (DAO) classes
 │   ├── model/         # 🏗️ Java model classes
 │   ├── view/          # 🎭 JSP files for UI
 ├── web/
 │   ├── assets/        # 🎨 CSS, JS, images
 │   ├── WEB-INF/       # ⚙️ Configuration files
 │   ├── index.jsp      # 🏠 Homepage
 ├── database/          # 🗄️ SQL scripts
 ├── README.md          # 📜 Project documentation
```

---

## 🔑 Test Accounts
You can use the following test accounts to explore the application’s features:

### 👤 **User Account:**
- 📧 **Email**: `thoi`
- 🔑 **Password**: `123`
- 🏆 **Access Level**: **Regular user** (can browse movies, manage bookings, and purchase tickets).

### 🛡️ **Admin Account:**
- 📧 **Email**: `abc`
- 🔑 **Password**: `123`
- 🏆 **Access Level**: **Admin** (can manage movies, customers, schedule types, and revenue reports via the Admin Panel).

---

## 🤝 Contribution
Feel free to **fork this project** and contribute by **submitting pull requests**. 🚀

---

## 📜 License
This project is licensed under the **MIT License**.

---

## 📩 Contact
For any inquiries or support, please reach out to **`phanthoi1101@gmail.com`**. 💌 Happy coding! 🎉


