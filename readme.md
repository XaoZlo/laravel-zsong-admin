#Laravel 6 + Laravel Admin (z-song) Boilerplate
This is a boilerplate created for fast start project, with admin panel.

Includes:
* [encore/laravel-admin](https://github.com/z-song/laravel-admin)
* [laravel-admin-ext/helpers](https://github.com/laravel-admin-extensions/helpers)
* [barryvdh/laravel-ide-helper](https://github.com/barryvdh/laravel-ide-helper)
##Install
```bash
# Clone repo in the directory you are in
$ git clone git@github.com:XaoZlo/laravel-zsong-admin.git .
$ git remote rm origin
$ composer install
# Set up your .env file
$ php artisan migrate --seed
$ php artisan admin:create-user
```
Enjoy!
