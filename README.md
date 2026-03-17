# Ponza Hotel

Aplicación web desarrollada como proyecto académico para la asignatura **Calidad de Ingeniería**.  
El sistema simula la gestión y visualización de los servicios de un hotel de lujo, permitiendo administrar información relacionada con habitaciones, reservas, clientes, spa, restaurantes, eventos y otros servicios complementarios.

## Descripción del proyecto

**Ponza Hotel** es una aplicación construida con **Spring Boot**, **Thymeleaf**, **Spring Data JPA** y **H2 Database**.  
Su propósito es ofrecer una plataforma web donde se pueda visualizar la información principal del hotel desde la parte pública del sitio y, al mismo tiempo, gestionar diferentes módulos administrativos mediante operaciones CRUD.

El proyecto está orientado a la organización de servicios hoteleros y a la administración de datos de forma estructurada, aplicando una arquitectura por capas compuesta por:

- **Controladores**
- **Servicios**
- **Repositorios**
- **Entidades**
- **Vistas HTML con Thymeleaf**

## Objetivo

Desarrollar una aplicación web para la gestión integral de un hotel, permitiendo administrar servicios, habitaciones, reservas, clientes, spa, restaurantes y eventos, aplicando buenas prácticas de desarrollo de software y una estructura mantenible.

## Funcionalidades principales

### Parte pública
- Página principal del hotel
- Visualización de habitaciones
- Visualización de restaurantes
- Visualización de servicios
- Visualización de spa
- Visualización de eventos
- Galería e historia del hotel
- Página de contacto
- Página de reservas
- Inicio de sesión y registro de clientes

### Parte administrativa
El sistema incluye módulos CRUD para la gestión de:

- Clientes
- Administradores
- Operadores
- Reservas
- Habitaciones
- Tipos de habitación
- Características de tipos de habitación
- Amenidades del hotel
- Restaurantes
- Detalles de restaurante
- Platos del menú
- Chefs
- Tratamientos de spa
- Instalaciones de spa
- Paquetes de spa
- Etiquetas de paquetes de spa
- Tipos de evento
- Espacios para eventos
- Servicios para eventos
- Consumos de servicios

## Tecnologías utilizadas

- **Java 17**
- **Spring Boot 3**
- **Spring Web**
- **Spring Data JPA**
- **Thymeleaf**
- **H2 Database**
- **Maven**
- **HTML, CSS y JavaScript**

## Arquitectura del proyecto

El proyecto está organizado siguiendo una estructura por capas:

```text
src/main/java/com/example/demo
│
├── controller     -> Controladores de la aplicación
├── entitys        -> Entidades del sistema
├── repository     -> Interfaces JPA para acceso a datos
├── service        -> Lógica de negocio![WhatsApp Image 2026-03-17 at 3 14 32 PM](https://github.com/user-attachments/assets/55e6a512-6027-4aed-9086-4146f97ecffe)
└── DataLoader     -> Carga inicial de datos de prueba


![WhatsApp Image 2026-03-17 at 3 14 32 PM](https://github.com/user-attachments/assets/5e6045c5-2e72-4d57-b5dc-cb0a6bf91590)
