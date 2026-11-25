# Spring Boot Hello REST API

A simple Spring Boot application that exposes a REST endpoint returning a JSON "Hello, World!" response.

## Tech Stack
- Java 17
- Spring Boot (Spring Web)
- Maven

## Project Structure
```
hello/
├── pom.xml
└── src/main/java/com/example/hello/
    ├── HelloApplication.java
    └── HelloController.java
```

## Endpoint

| Method | URL      | Description                     |
|--------|----------|---------------------------------|
| GET    | `/hello` | Returns a Hello, World! message |

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Start the application:
   ```bash
   mvn spring-boot:run
   ```
3. Open http://localhost:8080/hello in your browser.

## Sample Response
```json
{"message":"Hello, World!"}
```

## Implementation Steps
1. Created a Spring Boot project using Spring Initializr with the Spring Web dependency.
2. Added a `@RestController` class, `HelloController`.
3. Defined a `@GetMapping("/hello")` method that returns a `Map`.
4. Ran the app and tested it in the browser.
5. Verified the JSON response.git pull origin main --allow-unrelated-histories
