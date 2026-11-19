# Sistema web de gestión de restaurante

Proyecto integrador de DSI406 Tecnología Backend (Laravel + PostgreSQL).

Gestión de pedidos, cocina, mesas, caja y reportes de ventas.

## Requisitos

- PHP 8.3 o superior con pdo_pgsql
- Composer 2 y PostgreSQL

## Instalación

1. git clone https://github.com/Paulo-124/restaurante.git
2. cd restaurante
3. composer install
4. copy .env.example .env
5. php artisan key:generate
6. Crear la base de datos restaurante en PostgreSQL
7. php artisan migrate
8. php artisan serve

Autor: Paulo César Huallpa Romero