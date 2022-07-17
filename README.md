## Usar el core

PARA CLONAR CORE EN UNA CARPETA EJEMPLO CORE2

git clone https://github.com/moranhector/core.git core2

CREAR DATABASE
Renombrar .env.example
Configurar la base de datos
composer update
composer install
php artisan key:generate
php artisan migrate
Crear repositorio en Github

## Creación del core


composer create-project --prefer-dist laravel/laravel core

cd core

composer require laravel/breeze:1.9.2

npm install
npm run dev
php artisan migrate

CREACION DE REPOSITORIO EN GITHUB

En GitBash
echo "# core" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/moranhector/core.git
git push -u origin main

Configuré databases.php
           'charset' => 'utf8',
            'collation' => 'utf8_unicode_ci',

 


instalar CRESTAPP

composer require crestapps/laravel-code-generator --dev

laravel DebugBAr


composer require barryvdh/laravel-debugbar --dev

En GitBash
git add .
git commit -m "laravel debugbar y crestapp"
git branch -M main