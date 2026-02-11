Library Management System (Java Servlet + JDBC + Oracle)

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
<img width="1867" height="959" alt="Screenshot 2026-02-11 111228" src="https://github.com/user-attachments/assets/550aea6c-124c-4def-866b-c30b8f49456c" />

<img width="1919" height="964" alt="Screenshot 2026-02-11 111610" src="https://github.com/user-attachments/assets/bf152476-1db6-4c1e-9da9-838496c290a1" />

<img width="1910" height="971" alt="Screenshot 2026-02-11 111704" src="https://github.com/user-attachments/assets/b23b1fd2-01c7-4068-92cf-7141e017b3eb" />



