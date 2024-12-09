# Desa Wisata Papua Tengah


## Tech Stack

-   **Client :** Tailwind, Blade Template
-   **Server :** PHP with Laravel
-   **DBMS   :** MySQL



```bash
  cd desa-wisata
```

Run the command

```bash
  composer update
```

Or

```bash
  composer install
```

Copy the .env file from .env.example.

```bash
  cp .env.example .env
```



```bash
  DB_CONNECTION=mysql
  DB_HOST=127.0.0.1
  DB_PORT=3306
  DB_DATABASE=db_desawisata
  DB_USERNAME=root
  DB_PASSWORD=
```


  APP_LOCALE=id
```

Generate key

```bash
  php artisan key:generate
```

Create symlink

```bash
  php artisan storage:link
```

Migrate database

```bash
  php artisan migrate
```

Run User Seeder

```bash
  php artisan db:seed --class=UserSeeder
```

Install node_modules

```bash
  npm i
```

Run npm run dev

```bash
  npm run dev
```

