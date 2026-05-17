# ms-productos

Microservicio desarrollado con Spring Boot para la gestión de productos.

## Tecnologías utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Neon Database
- Docker
- Render
- Maven

## Endpoints

### Crear producto
POST /api/productos

### Listar productos
GET /api/productos

### Buscar producto por ID
GET /api/productos/{id}

### Actualizar producto
PUT /api/productos/{id}

### Eliminar producto
DELETE /api/productos/{id}

## Variables de entorno necesarias

- PORT=8080
- DB_URL=jdbc:postgresql://ep-billowing-sea-acqfx3bn-pooler.sa-east-1.aws.neon.tech/neondb?sslmode=require
- DB_USERNAME=neondb_owner
- DB_PASSWORD=npg_EdAGe9L1xkjK

## Instrucciones para ejecutar en local

1. git clone https://github.com/wendytamayo/ms-productos.git

2. Configurar variables de entorno en IntelliJ, en properties:

- PORT=8081
- DB_URL=jdbc:postgresql://localhost:5432/productos
- DB_USERNAME=postgres
- DB_PASSWORD=*****

3. ejecutar:
   ./mvnw spring-boot:run

## Instrucciones básicas de despliegue

- Crear Dockerfile
- Subir proyecto a GitHub
- Crear Web Service en Render
- Configurar variables de entorno
- Desplegar servicio
- URL del servicio desplegado

## URL del servicio desplegado
https://ms-productos-30rp.onrender.com/api/productos