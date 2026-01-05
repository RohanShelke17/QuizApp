🧠 Quiz App – Spring Boot

A RESTful Quiz Application built using Spring Boot that allows users to manage questions, create quizzes, and submit responses. 
This project demonstrates core backend concepts such as REST APIs, JPA, database interaction, and layered architecture.



🚀 Features

📌 Add, update, delete quiz questions
📝 Create quizzes dynamically
✅ Submit quiz responses
📊 Evaluate answers and return results
🗄️ Database integration using JPA & Hibernate
🔄 RESTful APIs


🛠️ Tech Stack

Technology           	Description

Java	                Core programming language
Spring Boot	          Backend framework
Spring Data JPA	      ORM & database access
Hibernate	            JPA implementation
MySQL                	Database
Maven	                Dependency management
Postman	              API testing


📂 Project Structure
quizapp
│
├── src/main/java/Quizapp
│   ├── controller
│   ├── service
│   ├── dao
│   ├── model
│   └── QuizappApplication.java
│
├── src/main/resources
│   └── application.properties
│
└── pom.xml




⚙️ Setup & Run Instructions
1️⃣ Clone the Repository
git clone https://github.com/your-username/quizapp.git
cd quizapp



2️⃣ Configure Database

Edit application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/quizdb
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

You may also use H2 database for testing.



3️⃣ Run the Application
mvn spring-boot:run

or run QuizappApplication.java from your IDE.



🔗 API Endpoints (Sample)

Method	  Endpoint	        Description
GET	      /questions	      Get all questions
POST	    /question/add   	Add a new question
POST	    /quiz/create	    Create a quiz
POST	    /quiz/submit	    Submit quiz answers


🧪 Testing
Use Postman to test the REST APIs.


📌 Future Enhancements
🔐 JWT Authentication & Authorization
👤 User roles (Admin / User)
🎨 Frontend using React
📈 Score history & analytics
🧾 Pagination & filtering
🤝 Contributing


Contributions are welcome!
Feel free to fork the repository and submit a pull request.



👨‍💻 Author
Rohan Shelke
📧 Email: rohanshelke0645@gmail.com


⭐ If you like this project, give it a star!
