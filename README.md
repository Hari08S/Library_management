-Library Management System (Java Servlet + JDBC + Oracle)

A simple Library Management System developed using Java Servlets, JDBC, HTML, and Oracle Database.  
This project allows users to add and view books along with author details using MVC architecture.

 Features

Add a new book
View book details
Store and fetch author information
Oracle Database integration using JDBC
MVC Architecture (Servlet → Service → DAO → Database)


 Technologies Used

- Java (JDK 8 )
- Java Servlets
- JDBC
- Oracle Database
- HTML
- Apache Tomcat Server
- Eclipse IDE

 Project Structure
 
Library_managements
│
├── src/main/java
│   ├── in.kce.book.bean
│   │   ├── AuthorBean.java
│   │   └── BookBean.java
│   │
│   ├── in.kce.book.dao
│   │   ├── AuthorDAO.java
│   │   └── BookDAO.java
│   │
│   ├── in.kce.book.service
│   │   └── Administrator.java
│   │
│   ├── in.kce.book.servlets
│   │   ├── MainServlet.java
│   │   └── ViewServlet.java
│   │
│   └── in.kce.book.util
│       └── DBUtil.java
│
├── src/main/webapp
│   ├── AddBook.html
│   ├── ViewBook.html
│   ├── Menu.html
│   ├── Failure.html
│   └── invalid.html
│
└── ojdbc8.jar
```

 How to Run the Project

1. Install Apache Tomcat Server
2. Import the project into Eclipse
3. Configure Tomcat in Eclipse
4. Right-click project → Run on Server
5. Open browser and visit:

Working Flow

1. Open Menu.html
2. Click ADD BOOK to add a new book
3. Click VIEW BOOK to view stored book details
4. Data is stored and retrieved from Oracle Database using JDBC

OUTPUT:


<img width="1919" height="964" alt="Screenshot 2026-02-11 111610" src="https://github.com/user-attachments/assets/c42b74f6-bb14-403b-a4fe-0dab01221b78" />


<img width="1910" height="971" alt="Screenshot 2026-02-11 111704" src="https://github.com/user-attachments/assets/84948b8e-5468-494e-9c55-6f634a46aab7" />


<img width="1867" height="959" alt="Screenshot 2026-02-11 111228" src="https://github.com/user-attachments/assets/7949f24e-a77d-4c75-a36d-e90f27bf7760" />




