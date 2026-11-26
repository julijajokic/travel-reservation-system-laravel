
## Running the laravel application

### 1. install dependencies

Open a terminal in the laravel project directory and run:

```bash
composer install
```

### 2. configure environment variables

Create a `.env` file by copying the `.env.example` file:

```bash
cp .env.example .env
```

### 3. generate application key

```bash
php artisan key:generate
```

### 4. configure the database

Open the `.env` file and configure the database connection:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

Create the database in MySQL using phpMyAdmin or another database management tool.

### 5. run database migrations

```bash
php artisan migrate
```

### 6. start the laravel development server

```bash
php artisan serve
```

open your browser and navigate to:

`http://127.0.0.1:8000`
