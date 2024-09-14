# Eureka Server

Eureka Server es un servidor de registro de servicios utilizado para la gestión de servicios en una arquitectura de microservicios. Actúa como un servicio de descubrimiento, permitiendo que los microservicios se registren y se descubran dinámicamente en el entorno.

## Arquitectura

El **Eureka Server** es parte de una arquitectura de microservicios compuesta por los siguientes componentes:

- **[Gateway Service](https://github.com/DanielRodado/GatewayService-ToDoList)**: Actúa como punto de entrada a todo el sistema y enruta las solicitudes a los diferentes microservicios.
- **[User Service](https://github.com/DanielRodado/UserService-ToDoList)**: Servicio encargado de la gestión de usuarios.
- **[Task Service](https://github.com/DanielRodado/TaskService-ToDoList)**: Servicio encargado de la gestión de tareas.

## Tecnologías Usadas

- **Java 17**
- **Spring Boot 3.x**
- **Spring Cloud Netflix Eureka**: Biblioteca de Spring Cloud que proporciona el servidor de descubrimiento Eureka para la gestión de servicios.

## Descripción del Servicio

### Funcionalidades

- **Registro de Servicios**: Permite que los microservicios se registren en el Eureka Server para que puedan ser descubiertos por otros servicios.
- **Descubrimiento de Servicios**: Facilita que los microservicios descubran y se comuniquen entre sí a través de un registro centralizado de servicios.

### Estructura del Proyecto

- **`src/main/java/com/example/eurekaserver`**: Código fuente del servidor Eureka.
  - **`Application.java`**: Clase principal para iniciar la aplicación Eureka Server.
- **`src/main/resources`**: Archivos de configuración.


