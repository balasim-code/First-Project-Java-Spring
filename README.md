# First REST API Spring – Task 1

This project represents Task 1 of the First REST API Spring course.
The main objective of this task is to initialize a Spring Boot application
and create a basic controller that handles an HTTP GET request and displays
content in a web browser.

---

## Features
- Spring Boot project initialized with Maven
- Simple Controller handling HTTP GET requests
- Greeting message generated using a request parameter
- Static content (text and image) displayed in the browser
- Uses @ResponseBody to return a plain text response for the root endpoint

---

## Application Output
**Requirement:**  
The application must correctly display a welcome message in a browser.

**Example URL:**  
http://localhost:8081/greeting?name=vistula

**Note:**  
The application runs on port 8081 because port 8080 was already in use on the local machine.

---

## Screenshot
![Application running in browser](screenshots/Vistula.png)

---

## Technologies Used
- Java 17
- Spring Boot
- Spring Web
- Maven

---

## How to Run
1. Clone or download the project
2. Open the project in IntelliJ IDEA
3. Wait for Maven to download all dependencies
4. Run the main class (`FirstProjectJavaSpringApplication`)
5. Open a web browser and go to:  
   http://localhost:8081/greeting?name=vistula

---

## API Endpoint

| Method | Endpoint  | Description |
|--------|-----------|-------------|
| GET    | /greeting | Returns a greeting message with the provided name |

---

## Author
Student: **Mustafa Asım Bal**  
Task: Task 1 – Spring Boot Project Setup & Basic Controller
