<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Reverb Chat

### Install and run app
``
php artisan serve
npm run dev
``

### Create livewire component for chat
``
php artisan make:livewire ChatMessage
``
### Install reverb using 
``
php artisan install:broadcasting
``

### run commands 
``
php artisan serve
npm run dev
php artisan reverb:start
``

### run reverb in debug mode
``
php artisan reverb:start --debug
``

### create model Message
``
php artisan make:model Message -m
``

### create event MessageSendEvent
``
php artisan make:event MessageSendEvent
``