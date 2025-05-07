# Bienvenido a MoneySaveBank 🏦

**MoneySaveBank** es una aplicación bancaria basada en microservicios, diseñada para simular operaciones comunes de una entidad financiera moderna. Está desarrollada principalmente con **Java** y **Spring Boot**, e incorpora tecnologías de infraestructura como **Docker**, **MySQL** y **Redis**.

## ¿Qué hace este sistema?

Este sistema permite realizar operaciones como autenticación de usuarios, consulta y gestión de cuentas bancarias, administración de tarjetas de crédito/débito, entre otras funciones. Está organizado bajo una arquitectura distribuida que promueve la escalabilidad, mantenibilidad y separación de responsabilidades entre servicios.

## Tecnologías utilizadas

- **Java & Spring Boot** – Desarrollo de microservicios.
- **Spring Cloud (Eureka, Gateway, Config Server)** – Descubrimiento, enrutamiento y configuración centralizada.
- **Docker** – Contenerización de servicios y bases de datos.
- **MySQL** – Base de datos relacional para persistencia de datos.
- **Redis** – Almacenamiento en memoria para gestión de tokens de sesión.

## Microservicios incluidos

- 🧾 **login-service**: Maneja la autenticación de usuarios.
- 💼 **accounts-service**: Administra cuentas bancarias por cliente.
- 💳 **cards-service**: Gestiona tarjetas asociadas a cuentas.
- 🔧 **config-server**: Provee configuración externa a todos los servicios.
- 📡 **eureka-server**: Registro y descubrimiento de servicios.
- 🚪 **gateway-service**: Punto de entrada para las solicitudes externas.

## Demostración

A continuación, puedes ver una demostración del sistema en funcionamiento:

🎥 

## Autor

👤 **Octavio Ramses Cardona Ortiz**
