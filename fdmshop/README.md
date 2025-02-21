# FDM Shop

Welcome to the FDM Shop project! This project is a Django-based web application designed to manage an online shop. Below you will find detailed documentation to help you understand and contribute to the project.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

FDM Shop is an e-commerce platform built using Django. It provides a robust and scalable solution for managing products, orders, and customers. The project aims to offer a seamless shopping experience for users and an easy-to-manage interface for administrators.

## Features

- User authentication and authorization
- Product management (CRUD operations)
- Order management
- Shopping cart functionality
- Payment gateway integration
- Responsive design

## Installation

To get started with FDM Shop, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Zeffar/UNI_second_year/django/fdmshop.git
    cd fdmshop
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv env
    source env/bin/activate
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**

    ```bash
    python manage.py migrate
    ```

5. **Create a superuser:**

    ```bash
    python manage.py createsuperuser
    ```

6. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

## Configuration

Before running the project, you need to configure the following settings in `settings.py`:

- **Database:** Configure your database settings.
- **Email:** Set up email backend for sending notifications.
- **Static files:** Ensure static files are correctly configured.

## Usage

Once the server is running, you can access the application at `http://127.0.0.1:8000/`. Here are some key functionalities:

- **Admin Panel:** Access the admin panel at `http://127.0.0.1:8000/admin/` to manage products, orders, and users.
- **Product Listing:** Browse products and add them to the shopping cart.
- **Checkout:** Complete the purchase by providing shipping details and payment information
