# Fullstack Application

A modern fullstack application built with React, TypeScript, and Java Spring Boot.

## 🚀 Tech Stack

### Frontend
- **Framework**: React 18
- **Language**: TypeScript
- **Build Tool**: Vite
- **State Management**: Redux Toolkit
- **Styling**: SCSS
- **UI Components**: 
  - Ant Design
  - Material-UI
- **Form Handling**: React Hook Form
- **API Client**: Axios
- **Testing**: Jest, React Testing Library

### Backend
- **Framework**: Spring Boot
- **Language**: Java
- **Database**: 
  - PostgreSQL
  - MongoDB
- **ORM**: 
  - JPA/Hibernate
  - Spring Data MongoDB
- **Security**: Spring Security, JWT
- **API Documentation**: Swagger/OpenAPI
- **Testing**: JUnit, Mockito

## 📋 Prerequisites

- Node.js (v18 or higher)
- Java JDK (v17 or higher)
- PostgreSQL
- MongoDB
- Git

## 🛠️ Installation

### Frontend Setup

1. Clone the repository:
```bash
git clone [repository-url]
cd Application
```

2. Install dependencies:
```bash
npm install
```

3. Create environment file:
```bash
cp .env.example .env
```

4. Start development server:
```bash
npm run dev
```

### Backend Setup

1. Navigate to backend directory:
```bash
cd Backend
```

2. Configure database:
- Update `application.properties` with your database credentials
- Create necessary databases in PostgreSQL and MongoDB

3. Build and run:
```bash
./mvnw spring-boot:run
```

## 🔧 Configuration

### Frontend Environment Variables
```env
VITE_API_URL=http://localhost:8080
VITE_APP_NAME=Your App Name
```

### Backend Configuration
- Database configuration in `application.properties`
- JWT settings in `application.properties`
- CORS configuration in `WebConfig.java`

## 📁 Project Structure

### Frontend
```
src/
├── components/     # Reusable UI components
├── pages/         # Page components
├── assets/        # Static assets
├── styles/        # SCSS styles
├── utils/         # Utility functions
├── hooks/         # Custom React hooks
├── services/      # API services
├── types/         # TypeScript types
├── constants/     # Constants
├── context/       # React context
└── layouts/       # Layout components
```

### Backend
```
src/main/java/
├── config/        # Configuration classes
├── controller/    # REST controllers
├── service/       # Business logic
├── repository/    # Data access
├── model/         # Entity classes
├── dto/           # Data Transfer Objects
└── security/      # Security configuration
```

## 🧪 Testing

### Frontend Tests
```bash
npm test
```

### Backend Tests
```bash
./mvnw test
```

## 📚 API Documentation

Access Swagger UI at: `http://localhost:8080/swagger-ui.html`

## 🔐 Authentication

The application uses JWT for authentication. Include the token in requests:
```javascript
Authorization: Bearer <your-token>
```

## 🚀 Deployment

### Frontend
```bash
npm run build
```

### Backend
```bash
./mvnw clean package
```

## 📝 License

This project is licensed under the MIT License.

## 👥 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, email [your-email] or open an issue in the repository.
