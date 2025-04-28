# Fullstack Application

A modern fullstack application built with React, TypeScript, and Java Spring Boot, featuring real-time capabilities with WebSocket and GraphQL. This application is optimized for medium to large-scale projects with its modular architecture and high-performance build system.

## 🚀 Tech Stack

### Frontend (Application/)
- **Framework**: React 19
- **Language**: TypeScript 5.7
- **Build Tool**: Vite 6.3 with SWC
  - **SWC (Speedy Web Compiler)**:
    - Rust-based compiler, 20x faster than Babel
    - Zero-config TypeScript support
    - Built-in JSX transform
    - Automatic React Refresh
    - Tree-shaking optimization
    - Fast development server startup
- **Styling**: SCSS
- **Development Tools**:
  - ESLint 9.22
  - TypeScript ESLint
  - React Refresh
  - React Hooks ESLint Plugin

### Backend (danhdoan/)
- **Framework**: Spring Boot 3.4.5
- **Language**: Java 21
- **API Types**:
  - REST API (WebFlux)
  - GraphQL
  - WebSocket
- **Documentation**: OpenAPI/Swagger UI
- **Testing**:
  - Spring Boot Test
  - Reactor Test
  - GraphQL Test

## 🏗️ Application Architecture

### Frontend Architecture
- **Modular Structure**: 
  - Feature-based organization
  - Reusable components
  - Shared utilities and hooks
  - Type-safe API integration
- **Performance Optimizations**:
  - SWC for fast compilation
  - Code splitting
  - Lazy loading
  - Optimized asset loading
- **Development Experience**:
  - Hot Module Replacement (HMR)
  - Fast refresh
  - Type checking
  - Linting

### Backend Architecture
- **Reactive Stack**:
  - WebFlux for non-blocking I/O
  - Reactive streams
  - Event-driven architecture
- **API Layer**:
  - REST endpoints
  - GraphQL schema
  - WebSocket handlers
- **Scalability**:
  - Stateless design
  - Horizontal scaling support
  - Connection pooling

### Project Scale
This architecture is suitable for:
- **Medium to Large Applications**:
  - Enterprise applications
  - Real-time collaboration tools
  - Data-intensive dashboards
  - Multi-user systems
- **Key Features**:
  - Scalable frontend and backend
  - Real-time capabilities
  - Type safety
  - High performance
  - Developer productivity

## 📋 Prerequisites

- Node.js (v18 or higher)
- Java JDK 21
- Git

## 🛠️ Installation

### Frontend Setup

1. Navigate to frontend directory:
```bash
cd Application
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start development server (runs on port 3001):
```bash
npm run dev
# or
yarn dev
```

### Backend Setup

1. Navigate to backend directory:
```bash
cd danhdoan
```

2. Build and run (runs on port 8080):
```bash
./mvnw spring-boot:run
```

## 🔧 Configuration

### Frontend
- Development server runs on port 3001
- Configured with TypeScript strict mode
- ESLint for code quality
- SCSS for styling

### Backend
- Server runs on port 8080
- GraphQL endpoint: `/graphql`
- WebSocket endpoint: `/ws`
- Swagger UI: `/swagger-ui.html`

## 📁 Project Structure

### Frontend (Application/)
```
Application/
├── src/            # Source code
├── public/         # Static assets
├── node_modules/   # Dependencies
├── package.json    # Dependencies and scripts
├── vite.config.ts # Vite configuration
├── tsconfig.json  # TypeScript configuration
└── eslint.config.js # ESLint configuration
```

### Backend (danhdoan/)
```
danhdoan/
├── src/
│   ├── main/
│   │   ├── java/   # Java source code
│   │   └── resources/ # Configuration files
│   └── test/       # Test code
├── pom.xml         # Maven configuration
└── mvnw           # Maven wrapper
```

## 🧪 Testing

### Frontend
```bash
npm run lint
```

### Backend
```bash
./mvnw test
```

## 📚 API Documentation

Access Swagger UI at: `http://localhost:8080/swagger-ui.html`

## 🔄 Communication

The application supports multiple communication protocols:

1. **REST API** (WebFlux)
   - Endpoint: `http://localhost:8080/api/*`
   - Methods: GET, POST, PUT, DELETE

2. **GraphQL**
   - Endpoint: `http://localhost:8080/graphql`
   - Playground: `http://localhost:8080/graphiql`

3. **WebSocket**
   - Endpoint: `ws://localhost:8080/ws`
   - Real-time bidirectional communication

## 🚀 Deployment

### Frontend
```bash
npm run build
# or
yarn build
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

For support, please open an issue in the repository.
