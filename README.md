# Atrak - Luxury Perfume E-Commerce Platform 🌸

A full-stack perfume e-commerce platform built with modern web technologies.
The project provides a complete shopping experience with product browsing, custom perfume creation, cart management, checkout flow, and backend APIs.

##  Live Demo

Frontend:
https://abdo1454.github.io/atrak-frontend

## 📌 Project Overview

Atrak is a luxury perfume store that allows users to:

* Browse perfumes and categories
* View product details
* Create custom perfumes using the perfume builder
* Add products to cart
* Complete checkout process
* Manage user authentication
* Contact support

## 🛠️ Technologies Used

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* Axios
* Context API

### Backend

* Laravel 12
* PHP
* MySQL
* Laravel Sanctum
* RESTful API

## ✨ Features

### User Features

* User registration and login
* Product listing
* Product search and filtering
* Product details
* Shopping cart
* Custom perfume builder
* Checkout system
* Order creation

### Admin Features

* Dashboard
* Product management
* Order management
* Category management

## 📂 Project Structure

```
Atrak-Fullstack
│
├── atrak-frontend
│   └── React Application
│
└── atrak-backend
    └── Laravel API
```

## ⚙️ Installation

### Frontend

```bash
cd atrak-frontend
npm install
npm run dev
```

### Backend

```bash
cd atrak-backend
composer install
php artisan key:generate
php artisan migrate
php artisan serve
```

## 🔐 Environment Setup

Create `.env` file in Laravel backend:

```
DB_DATABASE=your_database
DB_USERNAME=root
DB_PASSWORD=
```

Then run:

```bash
php artisan migrate --seed
```

## 📸 Screenshots

(Add project screenshots here)

## 👨‍💻 Developer

Abdulrahim Elsayed

GitHub:
https://github.com/Abdo1454

## 📄 License

This project was developed as a graduation project and learning experience.
