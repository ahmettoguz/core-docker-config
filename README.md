<h1 id="top" align="center">🚢 v1.0.0 🚢</h1> 

<br/>

## 🔍 Table of Contents

- [Service Versions](#service-versions)
- [Features](#features)
- [Next Release Features](#next-release-features)
- [System Links](#system-links)
- [System Preperation](#system-preperation)
- [System Startup](#system-startup)
 
<br/>

<h2 id="service-versions">🧩 Service Versions</h2> 

| Service                                       | Version                                                                                                                                                                                            |
|-----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| core-docker-config                            | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-docker-config/tree/v1.0.0)                            |
| core-java-spring-boot-rest-api                | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-java-spring-boot-rest-api/tree/v1.0.0)                |
| core-mocha-api-automation-test                | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-mocha-api-automation-test/tree/v1.0.0)                |
| core-database-initializer-alpine-mysql-client | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-database-initializer-alpine-mysql-client/tree/v1.0.0) |
| core-mysql                                    | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-mysql/tree/v1.0.0)                                    |
| core-phpmyadmin                               | [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=4A154B&color=233838)](https://github.com/ahmettoguz/core-phpmyadmin/tree/v1.0.0)                               |

<br/>

<h2 id="features">🔥 Features</h2>

### Core Docker Config

+ **Docker-Compose Configuration:** Comprehensive Docker-Compose configuration for managing service orchestration.

### Core Java Spring Boot Rest Api

+ **Relational Database Management:** Efficient handling of relational data with ORM, supporting one-to-one, one-to-many, and many-to-many relationships.
+ **Hot Reload:** Changes in the codebase can be instantly reflected without needing to restart the application.
+ **Environment Configuration:** Configurations have been adjusted for enhanced flexibility.
+ **AOP:** Aspect-Oriented Programming handles authentication and authorization separately from business logic, ensuring security across the application.
+ **Lombok:** Lombok is used to eliminate boilerplate code for better readability and maintainability.
+ **JWT Authentication:** User authentication and authorization are managed with JSON Web Tokens for secure, stateless sessions.
+ **Exceptions:** The application manages both custom and global exceptions for error handling.
+ **Swagger Documentation:** Comprehensive API documentation integrated for documentation and testing purposes.
+ **Dockerization:** The application is containerized for consistent deployment and scaling.
+ **Automated & Manual Testing:** Both automated and manual tests implemented for quality assurance.

### Core Mocha Api Automation Test

- **Parallel and Standard Modes:** Run tests in parallel for faster execution or in standard mode.
- **Auto-generated Reports:** Automatically generates detailed reports summarizing test results and highlighting any issues.
- **Postman Scripts:** Includes Postman scripts for testing all API endpoints, enabling manual testing and validation of functionality.
- **Database Cleanup:** Ability to clean database data, ensuring the environment is reset and ready for the next test run.
- **Comprehensive API Testing:** Tests all API endpoints for correctness.
- **Environment Variables**: Support for environment variables to manage configurations.

### Core Database Initializer Alpine MySQL Client

+ **Database Initialization:** Automatically sets up the MySQL database schema and loads seed data during container startup.
+ **Lightweight Alpine Base:** Built using an Alpine Linux base for minimal image size and faster startup.
+ **Felxibility:** Easily modify the default schema and data by updating SQL scripts in the project.
+ **Docker Containerization:** The application is containerized for consistent deployment and scaling.

### Core MySQL

+ **Docker Containerization:** The application is containerized for consistent deployment and scaling.
+ **Persistent Data:** Uses a volume to store MySQL data for reliability and consistency across restarts.

### Core PhpMyAdmin

+ **Dark Theme Interface:** A phpMyAdmin dashboard for managing MySQL databases with a dark theme.
+ **Docker Containerization:** The application is containerized for consistent deployment and scaling.

<br/>

<h2 id="next-release-features">🚧 Next Release Features</h2>

### Core Docker Config

+ **Centralized TLS Security:** Centralized TLS certificate configuration across all services.
+ **Auto-Renewal of Trusted TLS Certificates:** Automatic renewal of trusted TLS certificates to ensure uninterrupted security in production environments.
+ **Trusted TLS Certificates:** Secure communication between services using trusted SSL certificates managed by Traefik for production environment.
+ **Self-Signed TLS Certificates:** Secure communication between services using self-signed SSL certificates managed by Traefik for local development.
+ **Traefik Integration:** Traefik integrated for networking.
+ **Traefik Load Balancing:** Load balancing configured through Traefik for improved scalability and also local service development.
+ **Traefik Router:** Routing configured through Traefik for service communication without exposing port to public.
+ **Traefik Dashboard:** Dashboard integrated for monitoring and managing Traefik services, routers and prefixes.
+ **www to non-www Routing:** Traefik configured to handle routing from the 'www' subdomain to the non-www domain.
+ **Path Routing:** Traefik configured for path-based routing, directing traffic based on URL paths to specific services.

### Core Java Spring Boot Rest Api

- PostgreSQL integration.
- Plain response.
- Remove precedence key.
- Add Dto.
- Implement isDeleted.

<br/>

<h2 id="system-links">🔗 System Links</h2> 

| Service            | URL                                                        |
|--------------------|------------------------------------------------------------|
| Traefik Dashboard  | https://coreapp.com.tr/traefik/dashboard/#/                |
| Backend Swagger UI | https://coreapp.com.tr/backend/sw/swagger-ui/index.html    |

<br/>

<h2 id="system-preperation">🔧 System Preperation</h2>

* Create a new directory named `core`.
* Clone repositories.

```
git clone https://github.com/ahmettoguz/core-docker-config
git clone https://github.com/ahmettoguz/core-java-spring-boot-rest-api
git clone https://github.com/ahmettoguz/core-mocha-api-automation-test
git clone https://github.com/ahmettoguz/core-database-initializer-alpine-mysql-client
git clone https://github.com/ahmettoguz/core-mysql
git clone https://github.com/ahmettoguz/core-phpmyadmin
```

<br/>

#### Core Docker Config

* Update the domain name in the `traefik-conf/traefik-dynamic.yml` file, replacing current domain name with your domain name such as `localhost`.
* Place email address to `traefik-conf/treafik.yml`.

<br/>

### Core Mocha Api Automation Test

* Start the database.
* Initialize the database.
* Launch the backend server.
* Modify `.env` file for further configurations.
* Install dependencies

```
npm i
```

<br/>

### Core MySQL

* Modify `.env` file for further configurations.

<br/>

### Core PhpMyAdmin

* Modify `.env` file for further configurations.

<br/>

### Core Database Initializer Alpine MySQL Client

* Start the database.
* Modify the `.env` file to configure database credentials, host and database name.
* Replace the `init.sql` file with your custom SQL script to initialize the database schema and seed data.

<br/>

<h3 id="developer-mode">🧪 Developer Mode</h3>

### Core Java Spring Boot Rest Api

* Modify `application-dev.properties` file for further configurations.

<br/>

<h3 id="production-mode">⚡Production Mode</h3> 

### Core Java Spring Boot Rest Api

* Copy `application-dev.properties` to create `application-prod.properties`. Refer to `production-example.txt` for guidance.

<br/>
  
<h2 id="system-startup">🚀 System Startup</h2>

```
docker compose -p core build
docker compose -p core up -d
docker compose -p core up -d --build
docker compose -p core down

docker compose -p core build my-sql
docker compose -p core up -d my-sql
docker compose -p core up --build -d my-sql
docker compose -p core down my-sql

docker compose -p core build php-myadmin
docker compose -p core up -d php-myadmin
docker compose -p core up --build -d php-myadmin
docker compose -p core down php-myadmin

docker compose -p core build database-initializer-mysql
docker compose -p core up -d database-initializer-mysql
docker compose -p core up --build -d database-initializer-mysql
docker compose -p core down database-initializer-mysql

docker compose -p core build backend
docker compose -p core up -d backend
docker compose -p core up --build -d backend
docker compose -p core down backend
```

### [🔝](#top)