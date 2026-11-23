
## Running the Laravel Application

### 1. Install Dependencies

Open a terminal in the Laravel project directory and run:

```bash
composer install
```

### 2. Configure Environment Variables

Create a `.env` file by copying the `.env.example` file:

```bash
cp .env.example .env
```

### 3. Generate Application Key

```bash
php artisan key:generate
```

### 4. Configure the Database

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

### 5. Run Database Migrations

```bash
php artisan migrate
```

### 6. Start the Laravel Development Server

```bash
php artisan serve
```

Open your browser and navigate to:

`http://127.0.0.1:8000`
