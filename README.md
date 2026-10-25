# Actividad 0 · Usuarios activos con Ionic y Angular

## Aplicación publicada

https://users-app-ricardo-crespo.vercel.app/users

Práctica de Desarrollo de Interfaces (2.º DAM), correspondiente
a Ionic Intro.

- **Autor:** Ricardo Crespo
- **Repositorio:** usersApp_RicardoCrespo
- **Rama de trabajo:** desarrollo

## Objetivo

Crear una aplicación Ionic con Angular organizada en modelo,
servicio y página, utilizando TypeScript y operaciones asíncronas.

## Funcionamiento

La aplicación muestra los usuarios activos: Ana y Carlos.
Luis queda excluido porque su propiedad active es false.

Los datos son locales. El servicio simula una consulta con un
retardo de 500 ms; no necesita una API externa ni un backend.

## Estructura

- src/app/models/user.model.ts: interfaz User.
- src/app/services/users.service.ts: consulta y filtrado de usuarios.
- src/app/pages/users/: lógica y vista de la página.
- src/app/app.routes.ts: rutas y redirección inicial a /users.

## Tecnologías

Ionic 9, Angular 22, TypeScript y SCSS.

## Ejecución local

Requisitos: Node.js, npm e Ionic CLI.

Desde la carpeta del proyecto:

```bash
npm ci
ionic serve
```

Abre http://localhost:8100/users, o el puerto indicado por la terminal.

## Compilación

```bash
npm run build
```

El resultado se genera en www.

## Relación con la actividad 1.1

Este mismo proyecto se utilizó para la actividad 1.1, siguiendo
la indicación dada en clase: publicar la rama desarrollo en GitHub
y establecerla como rama predeterminada.
