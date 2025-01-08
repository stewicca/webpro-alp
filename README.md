# E-Commerce Application

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/stewicca/webpro-alp.git
    ```
2. Navigate to the project directory:
    ```bash
    cd webpro-alp
    ```
3. Install dependencies with Composer:
    ```bash
    composer install
    ```
4. Copy the `.env.example` file to `.env` and adjust the database configuration:
    ```bash
    cp .env.example .env
    ```
5. Generate the application key:
    ```bash
    php artisan key:generate
    ```
6. Migrate and seed the database:
    ```bash
    php artisan migrate --seed
    ```

## Docker Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/stewicca/webpro-alp.git
    ```
2. Navigate to the project directory:
    ```bash
    cd webpro-alp
    ```
3. Install dependencies with Composer:
    ```bash
    composer install
    ```
4. Copy the `.env.example` file to `.env` and adjust the database configuration:
    ```bash
    cp .env.example .env
    ```
5. Run the application:
    ```bash
    ./vendor/bin/sail up -d
    ```
6. Generate the application key:
    ```bash
    ./vendor/bin/sail artisan key:generate
    ```
7. Migrate and seed the database:
    ```bash
    ./vendor/bin/sail artisan migrate --seed
    ```

## Note

1. Home page is dummy
2. Product in Shop section
3. Shop is showing product between \$1 - $10000 as default
4. Admin email is: admin@example.com // After seeding database
5. Admin password is: password // After seeding database
