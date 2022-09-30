# Laravel-FB-Auth
Facebook Auth using Socialite

## Requirements
- Laravel 5.8^ or greater
- Composer
- Php 7.1^


### Getting started
Follow the instructions below:

1. Open CLI/CMD from `laravel-fb-auth` directory.

2. Run Command `composer install` to install required dependencies.

3. Create new DB `social`


4. Rename `env.example` to `.env` & Configure `.env` file to your DB configuration

```php
DB_HOST=127.0.0.1
DB_DATABASE=social
DB_USERNAME=root
DB_PASSWORD=
```

3. Run Command `php artisan migrate`.

4. Run `php artisan db:seed` to create test records using faker.

5. Start the server with `php artisan serve`

6. Server port starts with `http://127.0.0.1:8000`


### Custom User(Optional)
Note: wipe out `social` db records/tables before using the following:


1. Import `social.sql` to your DB and login via the following:

-Username: admin@outlook.com
-Password: qweqwe123


Your good to go!
