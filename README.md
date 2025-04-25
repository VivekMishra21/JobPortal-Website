
# JobPortal-Website
This is a job portal web application built with Spring Boot 3, Spring MVC, Thymeleaf, Spring Security, Spring Data JPA, Hibernate, and a MySQL database. It features a secure user registration and login system, a recruiter dashboard to post jobs, and a candidate dashboard to apply for jobs.

Table of Contents
1.Introduction
2.Features
3.Technologies
4.Installation
5.Usage
6.Contributing


1.Introduction :
This project is a Spring Boot application designed to create a job portal system. It includes functionalities like user registration, login, job posting by recruiters, and job application by candidates. The application leverages modern Java technologies and frameworks such as Spring Boot 3, Spring MVC, Spring Security, Spring Data JPA, and Thymeleaf for the front-end rendering. The backend is powered by Hibernate/JPA, and data is stored in a MySQL database.

2.Features :

![Home Page](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20113219.png)

User Registration and Login: Secure user registration and login system using Spring Security.

![Login Page](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20113305.png)

![Registration Page](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20113341.png)

Recruiter Dashboard: Allows recruiters to post job listings, manage them, and view applicants.

![Recruiter Dashboard](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20120347.png)

![Recruiter Setup Profile](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20113522.png)

Candidate Dashboard: Candidates can view job listings and apply for jobs.

![Candidate Dashboard](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20120427.png)

Job Posting by Recruiters: Recruiters can create job postings that are visible to candidates.

![Job Post](https://github.com/VivekMishra21/JobPortal-Website/raw/main/Screenshot%202025-04-25%20113628.png)

Security: Implementing user authentication and authorization using Spring Security.

Responsive Design: Ensures a user-friendly experience across all devices.

3.Technologies :
This project is built using the following technologies:

Spring Boot 3: A modern Java framework for building scalable web applications.

Spring MVC: For creating the web layer and handling HTTP requests.

Thymeleaf: A server-side Java template engine for rendering dynamic web pages.

Spring Security: Used to secure the application with authentication and authorization for user registration, login, and logout.

Spring Data JPA: For managing data persistence with JPA (Java Persistence API).

Hibernate/JPA: ORM (Object Relational Mapping) solution to interact with the MySQL database.

MySQL: Relational database management system to store user and job-related data.

Maven: For managing project dependencies and building the project.

4.Installation :
To run the project locally, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/JobPortal-Website.git
Navigate to the project directory:

bash
Copy
Edit
cd JobPortal-Website
Set up the MySQL database:

Create a database in MySQL (e.g., jobportal_db).

Update the application.properties file in src/main/resources with your MySQL database credentials:

properties
Copy
Edit
spring.datasource.url=jdbc:mysql://localhost:3306/jobportal_db
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
Build the project using Maven:

bash
Copy
Edit
mvn clean install
Run the project:

bash
Copy
Edit
mvn spring-boot:run
Open your browser and navigate to http://localhost:8080 to access the application.

5.Usage :
Once the application is up and running:

For Recruiters:

Sign up or log in as a recruiter.

Use the recruiter dashboard to post and manage job listings.

View candidates who have applied for jobs.

For Candidates:

Sign up or log in as a candidate.

Browse job listings and apply to the ones you are interested in.

6.Contributing :
We welcome contributions! To contribute:

Fork the repository.

Create a new branch for your feature or bugfix (git checkout -b feature/your-feature-name).

Make your changes.

Commit your changes (git commit -m 'Add feature').

Push to your forked repository (git push origin feature/your-feature-name).

Open a pull request.
