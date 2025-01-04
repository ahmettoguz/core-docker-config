<h1 id="top" align="center">Core <br/> Docker Config</h1> 

<br>

<div align="center">
    <img width=700 src="assets/banner/banner.png">
</div>

## 🔍 Table of Contents

- [About Project](#intro)
- [Technologies](#technologies)
- [Features](#features)
- [Releases](#releases)
- [Treafik Dashboard](#traefik-dashboard)
- [System Links](#system-links)
- [System Preperation](#system-preperation)
- [System Startup](#system-startup)
- [Contributors](#contributors)
 
<br/>

<h2 id="intro">📌 About Project</h2> 

This project aims to design a microarchitecture that integrates client-side and server-side components, uses Docker for containerization, enforces TLS security protocols, and configures reverse proxies.

<br/>

<h2 id="technologies">☄️ Technologies</h2>

### DevOps

&nbsp; [![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

&nbsp; [![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=black)](https://traefik.io/)

### Distribution

&nbsp; [![ALPINE-LINUX](https://img.shields.io/badge/Alpine_Linux-0D597F?style=for-the-badge&logo=alpine-linux&logoColor=white)](https://alpinelinux.org/)

### Build Tools

&nbsp; [![Apache Maven](https://img.shields.io/badge/apache_maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)](https://maven.apache.org/)

### ORM

&nbsp; [![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)](https://hibernate.org/)

### Database

&nbsp; [![Mysql](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)

&nbsp; [![Postgresql](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)

&nbsp; [![PHPMYADMIN](https://img.shields.io/badge/phpmyadmin-6C78AF?style=for-the-badge&logo=phpmyadmin&logoColor=white)](https://www.phpmyadmin.net/)

&nbsp; [![pgAdmin](https://img.shields.io/badge/pgadmin-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.pgadmin.org/)

### Security

&nbsp; [![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)](https://jwt.io/)

### Web

&nbsp; [![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

&nbsp; [![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)](https://spring.io/)

&nbsp; [![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot)](https://spring.io/projects/spring-boot)

&nbsp; [![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black)](https://tomcat.apache.org/)

&nbsp; [![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=Swagger&logoColor=white)](https://swagger.io/)

&nbsp; [![.Env](https://img.shields.io/badge/.ENV-ECD53F.svg?style=for-the-badge&logo=dotenv&logoColor=black)](https://www.ibm.com/docs/bg/aix/7.2?topic=files-env-file)

### Test

&nbsp; [![Mocha](https://img.shields.io/badge/Mocha-8D6748?style=for-the-badge&logo=Mocha&logoColor=white)](https://mochajs.org/)

&nbsp; [![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)

### Report

&nbsp; [![Mochawesome](https://img.shields.io/badge/MochAwesome-37474F?style=for-the-badge&logo=Mocha&logoColor=white)](https://mochajs.org/)

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


<h2 id="releases">🚢 Releases</h2> 

&nbsp; [![.](https://img.shields.io/badge/1.0.0-233838?style=flat&label=version&labelColor=470137&color=077521)](https://github.com/ahmettoguz/core-docker-config/tree/v1.0.0)

<h2 id="traefik-dashboard">🚥 Traefik Dashboard</h2> 

todo başlangıc
traefik gelince dashboard gelmeli
Monitor and manage services through the Traefik dashboard.

To view the dashboard visit: [`traefik`](https://sendsphere.com.tr/traefik/dashboard/#/).

<img width=500 src="assets/traefik/traefikDashboard.png">
todo bitis

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

### Core Docker Config

* Update the domain name in the `traefik-conf/traefik-dynamic.yml` file, replacing current domain name with your domain name such as `localhost`.
* Place email address to `traefik-conf/treafik.yml`.

### Core Mocha Api Automation Test

* Start the database.
* Initialize the database.
* Launch the backend server.
* Modify `.env` file for further configurations.
* Install dependencies

```
npm i
```

### Core MySQL

* Modify `.env` file for further configurations.

### Core PhpMyAdmin

* Modify `.env` file for further configurations.

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

<br/>

<h2 id="contributors">👥 Contributors</h2> 

<a href="https://github.com/ahmettoguz" target="_blank"><img width=60 height=60 src="https://avatars.githubusercontent.com/u/101711642?v=4"></a> 

### [🔝](#top)
