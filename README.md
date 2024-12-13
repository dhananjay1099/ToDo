# Todo Application

A simple Todo application built with Spring Boot, allowing users to manage their tasks efficiently. This project demonstrates the use of RESTful APIs, Spring Data JPA, and H2 database integration.

## Features

- **Create, Read, Update, Delete (CRUD)**: Manage todos with full CRUD functionality.
- **RESTful API**: Expose a RESTful API for easy integration with front-end applications.
- **In-Memory Database**: Utilize H2 database for quick setup and testing.

## Technologies Used

- **Java**: Programming language used for backend development.
- **Spring Boot**: Framework for building the application.
- **Spring Data JPA**: For database interactions.
- **H2 Database**: In-memory database for development and testing.
- **Maven**: Dependency management and build tool.

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo.git
   cd todo
   ```

2. Build the project:
   ```bash
   mvn clean install
   ```

3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

4. Access the API at `http://localhost:8080/api/todos`.

## API Endpoints

- `GET /api/todos`: Retrieve all todos.
- `GET /api/todos/{id}`: Retrieve a specific todo by ID.
- `POST /api/todos`: Create a new todo.
- `PUT /api/todos/{id}`: Update an existing todo.
- `DELETE /api/todos/{id}`: Delete a todo.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
