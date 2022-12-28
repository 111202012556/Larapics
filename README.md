<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Cara Install

### Kebutuhan Server

Aplikasi ini dapat dipasang pada server lokal dan online dengan spesifikasi berikut:

1. PHP 8 (dan mengikuti [server requirements Laravel 9.x](https://laravel.com/docs/9.x/deployment#server-requirements) lainnya),

### Langkah Instalasi

1. Clone Repo, pada terminal
2. `cd Larapics`
3. `composer install`
4. `cp .env.example .env`
5. `php artisan key:generate`
6. Buat Database dengan nama `larapics`
7. Import Database terlebih dahulu
8. `php artisan migrate --seed`
9. `php artisan storage:link`

### Menjalankan Server

- Terakhir jalankan `php artisan serve` untuk menjalankan server

## Documentation

- click here : https://pixinvent.com/demo/vuexy-html-bootstrap-admin-template/documentation/documentation-laravel-menu.html
- demo admin template : https://pixinvent.com/demo/vuexy-html-bootstrap-admin-template/html/ltr/vertical-menu-template/index.html

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
