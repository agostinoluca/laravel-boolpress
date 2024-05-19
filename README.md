# Primi approcci con Laravel Breeze (Repo test).

## Creiamo un progetto Laravel

```bash
composer create-project laravel/laravel:^10.0 my-title-app
```

## Installare il pacchetto Laravel Breeze

```bash
composer require laravel/breeze --dev
```

## Creiamo il nuovo scaffolding di default (usiamo Blade, no Dark mode, Pest)

```bash
php artisan breeze:install
```

## Modifichiamo lo scaffolding per poter utilizzare bootstrap

```bash
composer require pacificdev/laravel_9_preset
```

## Aggiunge/elimina alcune cartelle/file, rende tutto più adattabile a bootstrap

```bash
php artisan preset:ui bootstrap --auth
```

## Installo le dipendenze per il frontend

```bash
npm install
```

## Modifico l'estensione del file vite.config.js in vite.config.cjs

## Eseguo il comando npm run dev

```bash
npm run dev
```

## Popolare il database

```bash
php artisan db:seed --class=PostSeeder
```

## Paginazione link bootstrap

```php
{{ $posts->links('pagination::bootstrap-5') }}
```
