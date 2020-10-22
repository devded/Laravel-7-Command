# Necessary Laravel-7-Command

### Project Create

```
composer create-project --prefer-dist laravel/laravel:^7.0 blog
```

`Blog` is here project name

### Project

```
php artisan serve
```

### Create Controller

```
php artisan make:controller UserController
```

### Create Model

```
php artisan make:model Customer -m
```

### Migration

```
php artisan migrate
```
````
php artisan migrate:refresh
````


### Auth

````
composer require laravel/ui:^2.4
````
````
php artisan ui vue --auth
````

### Cache Clear

````
php artisan config:cache
````
````
php artisan cache:clear
````
````
php artisan config: clear
````