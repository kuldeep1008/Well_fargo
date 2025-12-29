Financial Advisor Client Management System
This project implements the data model for a Financial Advisor Client Management System using Spring Boot and JPA.
Technologies Used
Java
Spring Framework
Spring Data JPA
Hibernate
Maven
Project Description
The system is designed to manage multiple financial advisors and their clients.
Each advisor can manage multiple clients.
Each client has one portfolio, and each portfolio can contain multiple securities.
Entities
FinancialAdvisor – Manages multiple clients
Client – Belongs to a financial advisor
Portfolio – One-to-one with client
Security – Represents investments in a portfolio
Relationships
FinancialAdvisor → Client (One-to-Many)
Client → Portfolio (One-to-One)
Portfolio → Security (One-to-Many)

