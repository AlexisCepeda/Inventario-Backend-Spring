# 📦 Sistema de Inventario - Backend

Ejercicio CRUD desarrollado con **Spring Boot** para la gestión de inventario de objetos, permitiendo agregar, actualizar, listar y eliminar elementos de manera eficiente.

Los datos gestionados por este backend son consumidos por un **frontend desarrollado con Angular**, a través del cual el usuario puede interactuar con el sistema de forma visual e intuitiva.

## 🛠️ Tecnologías utilizadas

- **Spring Web**: Para la creación de controladores y el manejo de peticiones HTTP. Utiliza **Apache Tomcat** como servidor embebido.
- **Spring Data JPA**: Para la gestión de la persistencia de datos. Utiliza **Hibernate** como implementación por defecto.
- **MySQL**: Base de datos relacional utilizada para almacenar la información del sistema.
- **Lombok**: Para reducir la escritura de código repetitivo (getters, setters, constructores, etc.) y mejorar la legibilidad del proyecto.
- **Maven**: Como gestor de dependencias y automatización del ciclo de vida del proyecto.
- **Postman**: Herramienta utilizada para probar y documentar la API durante el desarrollo.

## 🔗 Frontend

El frontend del sistema fue desarrollado con **Angular** y consume los endpoints expuestos por este backend.  
🔗 [Repositorio del Frontend – Inventario-Frontend-Angular](https://github.com/AlexisCepeda/Inventario-Frontend-Angular)
