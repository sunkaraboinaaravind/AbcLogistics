# 🚚 ABC Logistics - Inventory & Logistics Management System

A robust Spring Boot application for managing warehouse logistics, carriers, and transportation orders. Designed with a clean REST API architecture and automated documentation.

## 🌟 Key Features
- **Admin Dashboard**: Manage addresses, carriers, trucks, and drivers.
- **Order Management**: Users can place, cancel, and track cargo orders.
- **Logistics Engine**: Intelligent assignment of trucks and carriers based on capacity and availability.
- **Automated Mail Service**: Real-time notifications for order confirmation, loading, and delivery.
- **Swagger Documentation**: Interactive API documentation for easy testing and exploration.
- **Docker Ready**: Pre-configured with a Dockerfile for easy deployment.

## 🚀 Getting Started
### 1. Live API Documentation
Once the project is running, you can interact with every endpoint through the Swagger UI:
`http://localhost:8080/swagger-ui/index.html`

### 2. Local Installation
1. Clone the repository.
2. Update `src/main/resources/application.properties` with your PostgreSQL credentials.
3. Run the application using the Maven wrapper:
   ```bash
   ./mvnw spring-boot:run
   ```

## 🐳 Docker Support
The project is containerized and ready for cloud deployment.
```bash
docker build -t abc-logistics .
docker run -p 8080:8080 abc-logistics
```

## 🛠️ Technology Stack
- **Backend:** Java 21, Spring Boot 3.5.6
- **Database:** PostgreSQL
- **ORM:** Spring Data JPA (Hibernate)
- **Documentation:** SpringDoc OpenAPI (Swagger UI)
- **CI/CD:** GitHub Actions