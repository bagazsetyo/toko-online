<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Toko Online

**BWA-TokoOnline** is an e-commerce web application that makes it easy to browse product packages and customize them as needed.

## ✨ Features

* Laravel 7.x
* Bootstrap 4
* Font Awesome

## 📚 Learning Laravel

Laravel has some of the best documentation and video tutorials among modern web application frameworks. Check out the [official Laravel documentation](https://laravel.com/docs) to get started.

Prefer video tutorials? [Laracasts](https://laracasts.com) offers over 1,500 high-quality videos covering Laravel, modern PHP, unit testing, JavaScript, and much more.

## ⚙️ Requirements

* PHP >= 7.3
* MySQL

## 🛠️ Installation

1. **Create a new database** using phpMyAdmin or your preferred database manager (e.g., `db_toko_online`).

2. **Extract the project files** to any directory on your machine.

3. Open your **terminal or command prompt** (e.g., via VS Code).

4. Navigate to the project folder:

   ```bash
   cd toko-online
   ```

5. Run the following commands:

   ```bash
   composer install
   npm install
   cp .env.example .env
   php artisan key:generate
   php artisan storage:link
   ```

6. Open the `.env` file and update your database configuration:

   ```env
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1          # Change if your database host is different
   DB_PORT=3306
   DB_DATABASE=db_toko_online # Change to the name of your database
   DB_USERNAME=root           # Change to your database username
   DB_PASSWORD=               # Enter your database password (leave blank if none)
   ```