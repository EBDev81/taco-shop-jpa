# Taco Shop JPA

## Descripción
El proyecto Taco Shop JPA es una aplicación de gestión para una tienda de tacos, desarrollada en Java utilizando JPA (Java Persistence API) en el Bootcamp de Keepcoding. La aplicación permite gestionar pedidos, ingredientes y usuarios, ofreciendo una solución completa para la administración de una tienda de tacos.

## Características
- **Gestión de Tacos:** CRUD completo (crear, leer, actualizar, eliminar) para los tacos.
- **Gestión de Ingredientes:** CRUD completo para los ingredientes.
- **Gestión de Pedidos:** Manejo de pedidos de tacos con integración de ingredientes.
- **Gestión de Usuarios:** Registro y autenticación de usuarios.
- **Persistencia de Datos:** Uso de JPA para la persistencia de datos en una base de datos relacional.

## Tecnologías Utilizadas
- **Lenguaje de Programación:** Java
- **Framework:** Spring Boot
- **Persistencia:** JPA/Hibernate
- **Base de Datos:** H2 (por defecto, pero fácilmente configurable para otras bases de datos)
- **Herramientas de Construcción:** Maven

## Instalación y Ejecución
Sigue los siguientes pasos para configurar y ejecutar la aplicación localmente:
Instrucciones:
```bash
1. Clona el repositorio:
   git clone https://github.com/EBDev81/taco-shop-jpa.git
2. Navega al directorio del proyecto: 
  cd taco-shop-jpa/taco-shop-jpa
3. Construye el proyecto usando Maven:
  mvn clean install
4. Ejecuta la aplicación:
  http://localhost:8080
```
##Endpoints API
- **GET /tacos:** Lista todos los tacos.
- **POST /tacos:** Crea un nuevo taco.
- **GET /tacos/{id}:** Obtiene los detalles de un taco específico.
- **PUT /tacos/{id}:** Actualiza un taco existente.
- **DELETE /tacos/{id}:** Elimina un taco.

