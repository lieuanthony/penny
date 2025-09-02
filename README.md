# Penny

A full-stack web application built with Angular frontend and Spring Boot backend.

## Project Structure

```
penny/
├── penny-frontend/     # Angular 20.2.x frontend application
├── penny-backend/      # Spring Boot 3.x backend API
└── README.md          # This file
```

## Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (v18 or later) - for the Angular frontend
- **npm** (comes with Node.js) - for frontend package management
- **Java** (JDK 21 or later) - for the Spring Boot backend
- **Maven** (for backend dependency management)

## Getting Started

### Backend (Spring Boot)

1. Navigate to the backend directory:
   ```bash
   cd penny-backend
   ```

2. Run the Spring Boot application:
   ```bash
   ./mvnw spring-boot:run
   ```
   
   Or on Windows:
   ```bash
   ./mvnw.cmd spring-boot:run
   ```

3. The backend API will be available at `http://localhost:8080`

### Frontend (Angular)

1. Navigate to the frontend directory:
   ```bash
   cd penny-frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   # or
   ng serve
   ```

4. Open your browser and navigate to `http://localhost:4200/`

## Development

### Frontend Development

The Angular frontend is located in the `penny-frontend/` directory.

**Available Scripts:**
- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run unit tests
- `npm run lint` - Run linting

**Code Scaffolding:**
```bash
ng generate component component-name
ng generate service service-name
ng generate module module-name
```

### Backend Development

The Spring Boot backend is located in the `penny-backend/` directory.

**Available Maven Commands:**
- `./mvnw spring-boot:run` - Start the application
- `./mvnw clean package` - Build the application
- `./mvnw test` - Run tests
- `./mvnw clean` - Clean build artifacts

## Building for Production

### Frontend
```bash
cd penny-frontend
npm run build
```
Build artifacts will be stored in the `penny-frontend/dist/` directory.

### Backend
```bash
cd penny-backend
./mvnw clean package
```
The JAR file will be created in the `penny-backend/target/` directory.

## Testing

### Frontend Tests
```bash
cd penny-frontend
npm test
```

### Backend Tests
```bash
cd penny-backend
./mvnw test
```

## Technology Stack

### Frontend
- **Angular** 20.2.x
- **TypeScript**
- **RxJS**
- **Angular CLI**

### Backend
- **Spring Boot** 3.5.x
- **Java** 21
- **Maven**

## API Documentation

The backend API documentation will be available at:
- Swagger UI: `http://localhost:8080/swagger-ui.html` (when configured)
- API Docs: `http://localhost:8080/api-docs` (when configured)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
