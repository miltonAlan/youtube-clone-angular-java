# Clon de YouTube - Proyecto Integrador

Este es un proyecto desarrollado como un clon de YouTube, utilizando **Spring Boot** para el backend y **Angular** junto con **TypeScript** para el frontend. La aplicación permite a los usuarios subir, visualizar y comentar videos, además de contar con un sistema de autenticación y recomendaciones de contenido.

## Tecnologías Utilizadas

- **Backend**:
  - **Spring Boot**: 2.5.4
  - **Java**: 11
  - **Maven**: 3.8.1
  - **MongoDB**: 4.4.6

- **Frontend**:
  - **Angular**: 12.0.0
  - **TypeScript**: 4.3.2
  - **Node.js**: 14.x

## Funcionalidades Principales

- **Subida de Videos**: Los usuarios pueden subir videos que se almacenan en el servidor.
- **Visualización de Videos**: Los usuarios pueden buscar y visualizar videos subidos por otros usuarios.
- **Sistema de Comentarios**: Los usuarios pueden comentar y dar likes/dislikes a los videos.
- **Recomendaciones**: La aplicación sugiere videos basados en el historial de visualización.
- **Autenticación de Usuarios**: Sistema de registro e inicio de sesión con JWT para proteger rutas.

## Requisitos de Instalación

### Backend

- [Java JDK 11](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Maven](https://maven.apache.org/download.cgi)
- [MongoDB](https://www.mongodb.com/try/download/community)

### Frontend

- [Node.js](https://nodejs.org/en/download/) (incluye npm)
- [Angular CLI](https://angular.io/cli)


## Información de Contacto

Si tienes alguna sugerencia, consulta o deseas contribuir a este proyecto, no dudes en contactarme a través de mi correo electrónico: [miltonpaucar99@gmail.com](mailto:miltonpaucar99@gmail.com).

## Clonar el Proyecto

Para clonar este repositorio en tu máquina local, abre una terminal y ejecuta:

```bash
   git clone https://github.com/miltonAlan/youtube-clone-angular-java.git
   cd backend
   mvn clean install
   mvn spring-boot:run
   cd frontend
   npm install
   ng serve