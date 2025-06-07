# Hello Spring Boot Application

A simple Spring Boot web application with a single endpoint that greets users.

## Features
- REST endpoint: `GET /hello/{name}` - Returns a greeting message
- Built with Spring Boot 2.7.0
- Java 11

## Prerequisites
- Java 11 or later
- Maven 3.6.3 or later

## Getting Started

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hello-spring.git
   cd hello-spring
   ```

2. Build the application:
   ```bash
   mvn clean install
   ```

3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

The application will start on `http://localhost:8080`.

## API Endpoint

- **GET** `/hello/{name}`
  - Returns: `Hello {name}`
  
  Example:
  ```
  GET /hello/John
  Response: Hello John
  ```

## Building for Production

To create an executable JAR file:

```bash
mvn clean package
java -jar target/hello-spring-0.0.1-SNAPSHOT.jar
```

## License

This project is licensed under the MIT License.
