Cinema Management Web Application

Overview

This project is a simple Cinema Web Application developed using Java Servlet and follows MVC (Model-View-Controller) architecture. The application is designed to manage cinemas, allowing administrators to manage movies, customers, showtimes, ticket booking... and also support users to search, show movies, book tickets...

Features

For Users:

Browse Movies: Display a list of available movies with details such as title, genre, duration, description, and poster.

Book Tickets: Select movies, showtimes, and seats to book tickets online.

View Booking History: Track past and upcoming bookings.

User Authentication & Authorization: Users can register, log in, and manage their accounts.

For Admin:

Movie Management: Add, update, and delete movie records.

Showtime Management: Manage schedules for different time slots.

Booking System: View and manage user bookings.

Customer Management: View customer details and booking history.

Admin Panel: Manage movies, users, and reservations with role-based access.

Technologies Used

Backend Framework: Java Servlet, JSP, JDBC

Database: MySQL

View Layer: JSP (JavaServer Pages) for dynamic rendering of pages

Frontend: HTML, CSS, Bootstrap, JavaScript

Authentication & Authorization: Servlet authentication with session management

Server: Apache Tomcat

Getting Started

To run this project locally, follow these steps:

Prerequisites

Java 8 or higher

MySQL Server

Apache Tomcat

IDE (Eclipse, IntelliJ IDEA, NetBeans, etc.)

Installation

Clone the repository:

git clone https://github.com/your-username/cinema-management.git

Set up the MySQL database:

Create a MySQL database named cinema_management and import the provided SQL script.

Update db.properties in src/main/resources/ with your database credentials.

Build and deploy the project on Apache Tomcat.

Access the application via http://localhost:8080/cinema-management/.

Folder Structure

 cinema-management/
 ├── src/
 │   ├── controller/    # Servlet controllers
 │   ├── dao/           # Data Access Object (DAO) classes
 │   ├── model/         # Java model classes
 │   ├── view/          # JSP files for UI
 ├── web/
 │   ├── assets/        # CSS, JS, images
 │   ├── WEB-INF/       # Configuration files
 │   ├── index.jsp      # Homepage
 ├── database/          # SQL scripts
 ├── README.md          # Project documentation

Test Accounts

You can use the following test accounts to explore the application’s features:

User Account:

Email: user@example.com

Password: 123456

Access Level: Regular user (can browse movies, manage bookings, and purchase tickets).

Admin Account:

Email: admin@example.com

Password: 123456

Access Level: Admin (can manage movies, showtimes, users, and bookings via the Admin Panel).

Contribution

Feel free to fork this project and contribute by submitting pull requests.

License

This project is licensed under the MIT License.

Contact

For any inquiries or support, please reach out to your-email@example.com. Happy coding!


