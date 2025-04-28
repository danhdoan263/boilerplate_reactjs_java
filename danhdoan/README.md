# Backend Application

A modern Spring Boot application with reactive programming support, GraphQL, and WebSocket capabilities.

## 🚀 Tech Stack

### Core Technologies
- **Framework**: Spring Boot 3.4.5
- **Language**: Java 21
- **Build Tool**: Maven
- **Reactive Stack**: WebFlux
- **API Types**:
  - REST API
  - GraphQL
  - WebSocket

### Development Tools
- **Testing**:
  - Spring Boot Test
  - Reactor Test
  - GraphQL Test
- **Documentation**: OpenAPI/Swagger UI
- **Development**: Spring Boot DevTools

## 🏗️ Project Structure

```
danhdoan/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── config/        # Configuration classes
│   │   │   ├── controller/    # REST controllers
│   │   │   ├── service/       # Business logic
│   │   │   ├── repository/    # Data access
│   │   │   ├── model/         # Entity classes
│   │   │   ├── dto/           # Data Transfer Objects
│   │   │   └── security/      # Security configuration
│   │   └── resources/
│   │       ├── application.properties
│   │       └── graphql/       # GraphQL schema
│   └── test/                  # Test code
├── pom.xml                    # Maven configuration
└── mvnw                       # Maven wrapper
```

## 📋 Prerequisites

- Java JDK 21
- Maven

## 🛠️ Installation

1. Build the application:
```bash
./mvnw clean install
```

2. Run the application (runs on port 8080):
```bash
./mvnw spring-boot:run
```

## 🔧 Configuration

### Server Configuration
- Port: 8080
- Context Path: /
- Development tools enabled

### API Endpoints
- REST API: `/api/*`
- GraphQL: `/graphql`
- GraphQL Playground: `/graphiql`
- WebSocket: `/ws`
- Swagger UI: `/swagger-ui.html`

### Development Configuration
- Hot reload enabled
- Debug port: 5005
- Test coverage reporting

## 🧪 Testing

Run all tests:
```bash
./mvnw test
```

Run specific test:
```bash
./mvnw test -Dtest=YourTestClass
```

## 🚀 Performance Features

### Reactive Programming
- Non-blocking I/O
- Backpressure handling
- Reactive streams
- Event-driven architecture

### API Layer
- REST endpoints with WebFlux
- GraphQL schema
- WebSocket handlers
- OpenAPI documentation

### Scalability
- Stateless design
- Horizontal scaling support
- Connection pooling
- Caching strategies

## 📦 Available Commands

- `./mvnw clean install` - Build the application
- `./mvnw spring-boot:run` - Run the application
- `./mvnw test` - Run tests
- `./mvnw spring-boot:build-image` - Build Docker image

## 🔄 Development Workflow

1. Create feature branch
2. Implement changes
3. Write tests
4. Run tests
5. Create pull request

## 📝 Best Practices

### Code Organization
- Clean architecture
- Domain-driven design
- SOLID principles
- Reactive patterns

### Performance
- Non-blocking operations
- Connection pooling
- Caching
- Batch processing

### Security
- Input validation
- Authentication
- Authorization
- CORS configuration

## 📚 API Documentation

Access Swagger UI at: `http://localhost:8080/swagger-ui.html`

## 📞 Support

For support, please open an issue in the repository. 