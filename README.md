Aquí tienes el archivo `README.md` en formato Markdown listo para usar:

---

# Airbnb Clone - Frontend

Este proyecto es el frontend de un clon de **Airbnb** desarrollado como una aplicación Full Stack utilizando **Angular 17** y **Spring Boot 3**. Permite a los usuarios explorar, buscar y reservar alojamientos con una interfaz moderna e intuitiva.

![Vista previa del proyecto](./assets/preview.png) <!-- Asegúrate de actualizar la ruta de la imagen -->

## Tabla de contenidos
- [Características clave](#características-clave)
- [Requisitos previos](#requisitos-previos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Compilación](#compilación)
- [Tecnologías utilizadas](#tecnologías-utilizadas)

---

## Características clave
- 📅 **Gestión de Reservas**: Reserva y gestión de propiedades para viajeros y propietarios.
- 🔍 **Búsqueda avanzada**: Filtrado por ubicación, fechas, número de huéspedes, camas y otros criterios.
- 🔐 **Autenticación y autorización**: Gestión de usuarios y roles mediante **Auth0** (OAuth2).
- 🏢 **Domain-Driven Design**: Arquitectura estructurada para escalabilidad y fácil mantenimiento.

---

## Requisitos previos

Antes de comenzar, asegúrate de tener instaladas las siguientes herramientas:
- [NodeJS 20.11 LTS](https://nodejs.org/dist/v20.11.1/node-v20.11.1.pkg)
- [Angular CLI v17](https://www.npmjs.com/package/@angular/cli)
- Un entorno de desarrollo compatible ([VSCode](https://code.visualstudio.com/download) o [IntelliJ](https://www.jetbrains.com/idea/download/))

---

## Instalación

Clona este repositorio y, en el directorio del proyecto, ejecuta el siguiente comando para instalar todas las dependencias necesarias:
```bash
npm install
```

---

## Uso

Inicia el servidor de desarrollo utilizando el siguiente comando:
```bash
ng serve
```
Luego, abre tu navegador y navega a `http://localhost:4200/`. La aplicación se actualizará automáticamente si realizas cambios en el código fuente.

---

## Compilación

Para construir la aplicación para producción, ejecuta:
```bash
ng build
```
Los archivos resultantes se almacenarán en el directorio `dist/`.

---

## Tecnologías utilizadas
- **Frontend**: Angular 17, PrimeNG para componentes visuales.
- **Backend**: Spring Boot 3 (Proyecto completo Full Stack).
- **Base de datos**: PostgreSQL.
- **Autenticación**: Auth0 (OAuth2).

---

Este archivo `README.md` está listo para integrarse en el proyecto y proporciona una estructura clara y profesional. No olvides colocar tu imagen en la carpeta `assets` o la ruta que prefieras, y actualizar el enlace en `![Vista previa del proyecto](./assets/preview.png)`.
