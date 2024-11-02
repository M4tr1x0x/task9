# Proyecto Task9 - Integración de AdminLTE en Laravel

## Descripción
Este proyecto integra el panel de administración AdminLTE en un sistema Laravel para gestionar secciones de una página.

## Requisitos
- PHP 7.4 o superior
- Composer
- Laravel 8
- Servidor local (XAMPP, WAMP, MAMP, LAMP, etc.)

## Instalación
1. Clona el repositorio.
2. Ejecuta `composer install` para instalar las dependencias.
3. Configura el archivo `.env` con los ajustes necesarios para la base de datos y el entorno.
4. Ejecuta `php artisan key:generate` para generar la clave de la aplicación.
5. Ejecuta `php artisan migrate` si necesitas migrar la base de datos para las sesiones.
6. Inicia el servidor de desarrollo con `php artisan serve`.

## Funcionalidades
- Panel de administración basado en AdminLTE.
- Menú lateral con opciones de navegación personalizadas (Home, Photos, Contact).
- Cada sección muestra contenido específico y resalta el elemento del menú activo.
- Personalización del pie de página con información del proyecto.

## Estructura del Proyecto
- `resources/views/layouts/app.blade.php`: Plantilla principal que incluye el menú y el pie de página.
- `resources/views/home.blade.php`: Vista de inicio (Home).
- `resources/views/photos.blade.php`: Vista de fotos (Photos).
- `resources/views/contact.blade.php`: Vista de contacto (Contact).
- `public/css/adminlte.min.css` y `public/js/adminlte.min.js`: Archivos de estilo y scripts de AdminLTE.

## Autor
Actividad realizada por Alejandro Andre Gonzalez Flores.
