# Task_Tracker
CRUD Understanding project 


 Step 1: Initialize Spring Boot Project
We’ll generate the base project using Spring Initializr.

🔧 Go to: https://start.spring.io/
Fill it like this:

Project-	Maven
Language	-Java
Spring Boot-	3.2.x (latest stable)
Group-	com.tasktracker
Artifact-	task-tracker
Name-	TaskTracker
Package Name	-com.tasktracker
Packaging	-Jar
Java-	17 or 21 (based on what you have)

📦 Dependencies (add these)

Spring Web
Spring Data JPA
PostgreSQL Driver (or H2 if you prefer testing)
Lombok
Validation 

🔽 Then click:
GENERATE 


moving on to step 2
Step 2: Create Task Entity (Java Class)
This class will represent our tasks table in the database.







after CRUD OPS

we will add DTOs to  separate our entity model from what we expose in our APIs. This keeps our domain model clean and gives you flexibility to change internal logic without affecting the API.


