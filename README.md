# Student Management System

A cloud-based serverless application to manage student data using AWS services.
This project demonstrates how to build a scalable and cost-efficient backend using serverless architecture.
This Serverless Student Management System is built using AWS cloud services to manage student data without maintaining servers. First, a table is created in Amazon DynamoDB to store student records such as ID, name, and department. Then a backend function is developed using AWS Lambda to process requests like adding or retrieving student data. The requests from the frontend are handled through Amazon API Gateway, which connects the web application to the Lambda function. A simple frontend interface is built using HTML and JavaScript and deployed using AWS Amplify. When a user submits student information through the web page, the request flows from the frontend to API Gateway, triggers Lambda to process the data, and finally stores or retrieves the data from DynamoDB, creating a fully scalable and serverless application

---

## Project Architecture

User → Frontend → API Gateway → Lambda → DynamoDB

The application allows users to add and retrieve student data without managing any servers.

---

## Technologies Used

Frontend:
- HTML
- JavaScript
- AWS Amplify

Backend:
- AWS Lambda

API Layer:
- API Gateway

Database:
- DynamoDB

Cloud Platform:
- AWS

---

## AWS Services Used

- AWS Amplify – Hosting frontend application
- AWS Lambda – Backend serverless functions
- API Gateway – Handles HTTP requests
- DynamoDB – Stores student data
- IAM – Access control

---

## Features

- Add new student data
- View student records
- Serverless architecture
- Highly scalable
- No server maintenance

---

## Architecture Diagram
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/e9275652-5d4c-4fc1-8052-cce46626e06b" />

---

## Project Structure
student-management-system
│
├── index.html
├── script.js
├── lambda_function.py
├── architecture-diagram.png
└── README.md

<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/383b0c3c-c53a-4229-827d-da0dd606ad6b" />
<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/7658a6e6-0447-4670-b3f1-d0dd8a302ee4" />
<img width="940" height="419" alt="image" src="https://github.com/user-attachments/assets/43af7c30-74a8-411a-9add-73d37e66fda7" />
<img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/5628ae1b-141c-49c6-bf3f-f6002e9c2971" />
<img width="1881" height="868" alt="image" src="https://github.com/user-attachments/assets/f90f2b66-2670-4fa9-9494-7f594c158730" />


## Author
Raksha Chanekar
Aspiring AWS & DevOps Engineer

LinkedIn:
(https://www.linkedin.com/in/raksha-chanekar-06b736272/)

GitHub Repo:
(https://github.com/RakshaChanekar/serverless-.git)

---

