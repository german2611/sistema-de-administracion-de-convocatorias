<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

# Sistema de Administración de Convocatorias para Auxiliares

Trabajo de Taller de Ingeniería de Software

### Pre-requisitos

- composer
- php >= 5.4.*
- wamp

### Instalación

- clonar en el directorio dentro del directorio C:\wamp64\www <br>
    <code>git clone https://github.com/dpa722/sistema-de-administracion-de-convocatorias</code>
- abrir el directorio recien clonado <br> 
    <code>cd carpeta_clonada </code>
- ejecutar <br> 
    <code>composer install</code>
- copiar el archivo .env.example a uno nuevo con el nombre .env <br>
    <code>cp .env.example .env</code>
- generar la key para que laravel pueda correr <br>
    <code>php artisan key:generate</code>
- Crearse una base de datos con el nombre cualquiera y cotejamiento utf8_bin
- editar el archivo .env las lineas <br>
    <code>DB_DATABASE = nombre_base_de_datos_creada</code> <br>
    <code>DB_USERNAME = tu_usuario </code><br>
    <code>DB_PASSWORD = tu_contraseña</code><br>
   
- limpiar la cache <br>
    <code>php artisan cache:clear</code>
- configurar la cache <br> 
    <code>php artisan config:cache</code>
- migrar la base de datos si se tiene alguna dentro el proyecto <br>
    <code>php artisan migrate</code>
- iniciar el servidor <br>
    <code>php artisan serve</code>
- ingresar en el navegador a http://localhost:8000/ y debera aparecerte la vista del index
