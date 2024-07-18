# Laravel Boilerplate

## Description

This repository is a Laravel boilerplate project designed to provide a solid foundation for new Laravel applications. It comes pre-configured with essential packages, authentication, and a basic project structure. Developers can fork this repository to quickly get started with their Laravel projects.

## Features

- **Authentication**: Basic authentication setup with Laravel UI.
- **Essential Packages**: Includes Laravel Debugbar for debugging and optional Laravel Telescope for monitoring.
- **Basic Structure**: Pre-defined folder structure for controllers, models, views, and routes.

## Prerequisites

- PHP >= 8.0
- Composer
- Node.js & npm
- A MySQL or MariaDB database

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/koudous25/laravel-boilerplate.git
   cd laravel-boilerplate

2. **Install dependencies**:
    ```bash
    composer install
    npm install

3. **Set up environment variables**:
   - Copy the **`.env.example`** file to **`.env`**:
        ```bash
        cp .env.example .env

    - Configure your database settings in the **`.env`** file:
        ```plaintext
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=your_database
        DB_USERNAME=your_username
        DB_PASSWORD=your_password

 4. **Generate application key**:
    ```bash
    php artisan key:generate

5. **Run migrations**:
   ```bash
   php artisan migrate

6. **Usage**:
   - **Start the development server**:
        ```bash
        php artisan serve

    - **Access the application**:
        Open your browser and go to **`http://localhost:8000`**.

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue to discuss what you would like to change.

## License
This project is open-sourced software licensed under the MIT license.

## Contact
For any questions or feedback, feel free to reach out to [https://github.com/koudous25/].
