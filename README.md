### Source

> https://www.youtube.com/watch?v=QyqrYdhSku0

### Install laravel app

> composer create-project laravel/laravel:^10.0 example-app

### Install Inertia

> composer require inertiajs/inertia-laravel
> /resources/views/app.blade.php -> <body>@inertia</body>

# Server side adapter

> php artisan inertia:middleware
> Kernel.php -> web routes -> HandleInertiaRequests.php

# Client side adapter
