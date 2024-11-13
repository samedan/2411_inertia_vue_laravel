### Source

> https://youtu.be/QyqrYdhSku0?si=HSh03PX4AMTTXD6n&t=1527

### Install laravel app

> composer create-project laravel/laravel:^10.0 example-app

### Install Inertia

> composer require inertiajs/inertia-laravel
> /resources/views/app.blade.php -> <body>@inertia</body>

# Server side adapter

> php artisan inertia:middleware
> Kernel.php -> web routes -> HandleInertiaRequests.php

# Client side adapter
