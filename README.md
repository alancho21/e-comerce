# 🛒 E-Commerce Backend (Laravel / PHP)

Este repositorio contiene la estructura backend y la lógica de negocio para una plataforma de E-Commerce. Fue desarrollado académicamente bajo la supervisión de un profesor titular, aplicando las mejores prácticas del patrón de diseño **MVC (Modelo-Vista-Controlador)**.

### 🚀 Características y Estructura
- **Framework:** Desarrollado sobre **Laravel 10** (PHP).
- **Autenticación (Auth):** Implementación completa del flujo de registro, login, verificación de correo y reseteo de contraseñas utilizando el sistema integrado de Laravel (Breeze/Sanctum).
- **Base de Datos:** Diseño relacional estructurado mediante `Migrations` y poblado con `Seeders`/`Factories` para pruebas de desarrollo.
- **Rutas y Controladores:** Separación lógica de rutas web (`web.php`) y rutas para consumo externo (`api.php`), gestionadas por controladores dedicados.
- **Vistas dinámicas:** Uso del motor de plantillas **Blade** para renderizar componentes de la interfaz de usuario (`.blade.php`), incluyendo layouts, modales y formularios seguros contra ataques CSRF.

### 🧑‍💻 Objetivo del Proyecto
El propósito principal de este desarrollo fue dominar la arquitectura interna de un framework moderno de backend en PHP, comprendiendo el ciclo de vida de una petición HTTP, la protección mediante Middlewares y la interacción segura con la base de datos a través del ORM Eloquent.

### 🛠️ Stack Tecnológico
- **Backend:** PHP, Laravel
- **Base de Datos:** MySQL / SQLite (vía Eloquent ORM)
- **Frontend / Vistas:** Laravel Blade, CSS/Tailwind (vía componentes integrados)
