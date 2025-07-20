# Laravel Sample Project

This is a sample Laravel 10 project created by following the [Stack Developers Laravel Crash Course](https://www.youtube.com/watch?v=-zQOkMnjXrw&list=PLo2t5xGpzGkfaZUOS6JoGixh_r-vz1LQJ).  
It demonstrates the fundamental features of the Laravel framework, including routing, controllers, Blade templating, database operations, and authentication.

---

## 📌 Features

- ✅ Laravel 10 Setup
- ✅ MVC Architecture
- ✅ Blade Templating Engine
- ✅ CRUD Operations (Create, Read, Update, Delete)
- ✅ Authentication System (Login/Register)
- ✅ Basic Frontend Styling

---

## 🛠️ Technologies Used

- PHP 8.x
- Laravel 10
- Composer
- MySQL / MariaDB
- Node.js & NPM
- Bootstrap (or Tailwind CSS if used)
- Git & GitHub

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/laravel-sample-project.git
cd laravel-sample-project
2. Install PHP Dependencies
bash
Copy
Edit
composer install
3. Install Frontend Assets
bash
Copy
Edit
npm install
npm run dev
4. Configure Environment File
bash
Copy
Edit
cp .env.example .env
php artisan key:generate
Open the .env file and update the following:

ini
Copy
Edit
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
5. Run Migrations
bash
Copy
Edit
php artisan migrate
6. Serve the Application
bash
Copy
Edit
php artisan serve
Visit: http://localhost:8000

📂 Folder Structure (optional)
arduino
Copy
Edit
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
│   └── views/
├── routes/
│   └── web.php
├── .env
└── README.md

🤝 Contributing
This is a personal learning project based on a YouTube tutorial.
However, feel free to fork the repository and explore or improve it!
