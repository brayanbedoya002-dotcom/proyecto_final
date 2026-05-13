# Proyecto CRUD de Usuarios

## Descripción
Aplicación web full-stack para gestionar usuarios con operaciones CRUD.

## Backend
- Node.js + Express
- MySQL
- Patrón MVC

## Instalación
1. Instalar Node.js
2. Ejecutar `npm install` en la raíz del proyecto
3. Configurar MySQL y ejecutar el script en `sql/create_database.sql`
4. Ejecutar `npm run dev` para desarrollo o `npm start` para producción

## API Endpoints
- GET /api/usuarios - Obtener todos los usuarios
- POST /api/usuarios - Crear usuario
- GET /api/usuarios/:id - Obtener usuario por ID
- PUT /api/usuarios/:id - Actualizar usuario
- DELETE /api/usuarios/:id - Eliminar usuario

## Pruebas
Usar Postman o similar para probar los endpoints.