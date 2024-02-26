# Proyecto de Desarrollo Web Full Stack Node - Trabajo Integrador de Práctica Profesional

## Introducción

Este proyecto es un desafío de codificación diseñado para simular un entorno de desarrollo de la vida real, ofreciendo a los participantes la oportunidad de demostrar sus habilidades en el desarrollo de una aplicación web completa. La aplicación consta de un frontend que consume datos de una API, ambos desarrollados desde cero. El frontend muestra información de aspirantes a trabajos, mientras que la API proporciona estos datos desde una base de datos MySQL.

## Objetivo

Desarrollar una aplicación web para una empresa multinacional de Recruiting de Recursos Humanos que permite a los usuarios ver un catálogo de aspirantes a trabajos. Este proyecto abarca la creación de una base de datos, el desarrollo de una API REST utilizando Node.js y Express, y el diseño y desarrollo de un frontend con React y Bootstrap.

## Tecnologías Utilizadas

- **Frontend**: React, Bootstrap/Tailwind, Axios/Fetch para llamadas a la API.
- **Backend (API REST)**: Node.js, Express, Sequelize para la conexión con la base de datos MySQL.
- **Base de Datos**: MySQL.

## Estructura del Proyecto

El proyecto está dividido en dos partes principales:

1. **Frontend**: Contiene el código fuente del cliente de la aplicación web, desarrollado con React.
2. **Backend**: Incluye la API REST desarrollada con Node.js y Express, además de la configuración de la base de datos MySQL.

### Directorio Frontend

frontend/
├── node_modules/
├── src/
│ ├── components/
│ ├── hooks/
│ ├── App.js
│ └── index.js
├── .eslintrc.json
├── package.json
└── vite.config.js


### Directorio Backend

backend/
├── node_modules/
├── src/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── app.js
├── package.json


## Instalación y Ejecución

### Requisitos Previos

- Node.js instalado.
- Gestor de paquetes NPM.
- MySQL instalado y configurado.

### Instrucciones

1. Clonar el repositorio:

git clone <URL-del-repositorio>

2. Instalar dependencias para el frontend:
```
npm install
cd frontend
```

3. Instalar dependencias para el backend:
```
cd ../backend
npm install
```
4. Crear y configurar el archivo `.env` en el backend con las credenciales de la base de datos.

5. Iniciar el servidor de desarrollo para el frontend:

```
npm run dev
```

6. Iniciar el servidor de desarrollo para el backend:

```
npm run dev
```


## Funcionalidades

Describir aquí las principales funcionalidades de la aplicación, incluyendo cómo interactúan el frontend y el backend.

Descripción del Proyecto
Este proyecto es parte de un desafío de codificación enfocado en el desarrollo web full stack, diseñado para simular un entorno de desarrollo profesional y ofrecer a los participantes una oportunidad valiosa de demostrar sus habilidades en la creación de aplicaciones web completas. El objetivo principal es desarrollar una aplicación web para una empresa multinacional de Recruiting de Recursos Humanos, que busca ofrecer a su público una plataforma moderna y eficiente para visualizar un catálogo de aspirantes a puestos de trabajo altamente demandados en la industria.

El desafío se divide en tres partes críticas: el desarrollo de una base de datos denominada "RecruitingRH" utilizando MySQL para gestionar la información de los aspirantes, la construcción de una API REST usando Node.js y Express para interactuar con la base de datos, y el diseño y desarrollo de un frontend interactivo utilizando la librería React junto con Bootstrap o Tailwind para el diseño de la interfaz de usuario. Esta estructura modular no solo refleja prácticas de desarrollo web modernas sino que también está diseñada con la reutilización del código en mente, preparando el proyecto para futuras expansiones o cambios en el stack tecnológico.

Puntos Clave del Proyecto:
Interfaz de Usuario Atractiva y Responsiva: Dado que un 80% de los usuarios acceden a través de navegadores de escritorio, mientras que una porción significativa también utiliza dispositivos móviles y tablets, la aplicación ha sido diseñada para ser completamente responsiva, asegurando una experiencia de usuario consistente y accesible en una amplia gama de dispositivos.

Frontend Dinámico y Moderno: El frontend, desarrollado con React, enfatiza la utilización de componentes funcionales y hooks para una gestión de estado y efectos secundarios eficiente, integración de rutas con React Router Dom para una experiencia de aplicación de página única (SPA), y el uso de Axios o Fetch para consumir la API REST de manera asíncrona, ofreciendo una interacción fluida y moderna.

Backend Robusto y Escalable: La API REST, desarrollada con Node.js y Express, sigue el patrón de diseño Modelo-Vista-Controlador (MVC) para una estructura de código organizada y mantenible. Esto facilita la gestión de los datos de aspirantes y la interacción con la base de datos MySQL, asegurando un rendimiento óptimo y seguridad en el manejo de la información.

Base de Datos Relacional Compleja: La base de datos MySQL está diseñada para almacenar y gestionar eficientemente los datos de los aspirantes, con una tabla específicamente dedicada a estos fines, asegurando que la información sea fácilmente accesible y actualizable a través de la API.

Este proyecto representa una oportunidad excelente para demostrar habilidades de desarrollo full stack, desde la concepción y diseño de la base de datos hasta la implementación de una interfaz de usuario interactiva y la lógica del servidor backend, todo dentro de un marco de trabajo colaborativo y profesional.