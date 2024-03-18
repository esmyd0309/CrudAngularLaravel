# Proyecto de Administración de Usuarios con Angular y Laravel

Este proyecto es una aplicación web desarrollada con Angular para el frontend y Laravel para el backend. Permite la administración de usuarios con funcionalidades de CRUD, paginación y filtros.

## Funcionalidades

- **CRUD de Usuarios:** Permite crear, leer, actualizar y eliminar usuarios.
- **Paginación:** Muestra los usuarios en una lista paginada.
- **Filtros:** Permite filtrar la lista de usuarios por departamento y cargo.

## Tecnologías Utilizadas

- **Frontend:** Angular, Bootstrap, HTML, CSS.
- **Backend:** Laravel, PHP, MySQL.

## Instalación

1. Clona el repositorio: `git clone https://github.com/tu-usuario/proyecto.git`
2. Instala las dependencias del frontend: `cd frontend && npm install`
3. Instala las dependencias del backend: `cd backend && composer install`
4. Configura la base de datos en el archivo `.env` del backend.
5. Ejecuta las migraciones del backend: ` php artisan migrate:fresh --seed`
6. Inicia el servidor de desarrollo del frontend: `ng serve`
7. Inicia el servidor de desarrollo del backend: `php artisan serve`
