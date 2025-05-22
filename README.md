# Bookstore Laravel Application

This is a simple Bookstore web application built with Laravel 12 (PHP 8.2+). It allows users to manage a collection of books, including creating, viewing, updating, and deleting book records. The project demonstrates modern Laravel features, database migrations, Eloquent ORM, and a Bootstrap-powered UI.

## Features
- List all books with pagination and search
- Add new books (title, author, ISBN, stock, price)
- Edit and update existing books
- View book details
- Delete books
- Responsive UI using Bootstrap 5
---

## 📺 Demo Video

<div align="center">
  
[![Book Store Laravel Demo](https://github.com/imrul-kayes-dipto/bookstoredipto/blob/master/resources/Dashboard.png)](https://youtu.be/9jz8aMoRDWw?si=OSyH0_clMTxyGudq)

</div>

> _Click the image above to watch the demo on YouTube!_


---
## Project Structure
- **app/Models/Book.php**: Eloquent model for books
- **app/Http/Controllers/BookController.php**: Controller handling CRUD operations
- **resources/views/**: Blade templates for UI (list, create, edit, show)
- **routes/web.php**: Web routes (resource controller for books)
- **database/migrations/**: Migrations for users, books, cache, jobs
- **database/factories/BookFactory.php**: Factory for seeding books
- **database/seeders/BookSeeder.php**: Seeder for populating books

## Getting Started

### Prerequisites
- PHP 8.2+
- Composer
- Node.js & npm

### Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd bookstoredipto
   ```
2. Install PHP dependencies:
   ```sh
   composer install
   ```
3. Install JavaScript dependencies:
   ```sh
   npm install
   ```
4. Copy the example environment file and set your configuration:
   ```sh
   cp .env.example .env
   php artisan key:generate
   ```
5. Run database migrations and seeders:
   ```sh
   php artisan migrate --seed
   ```
6. Start the development server:
   ```sh
   php artisan serve
   ```
7. (Optional) Start Vite for hot-reloading assets:
   ```sh
   npm run dev
   ```

Visit [http://localhost:8000](http://localhost:8000) in your browser.

## Testing
Run feature and unit tests with:
```sh
php artisan test
```

## License
This project is open-sourced under the MIT license.
