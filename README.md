# Project-manager

A Laravel application for managing projects and tasks.

## Features

- **Project Management**: Create, edit, and delete projects.
- **Task Management**: Add tasks to projects and track their progress.
- **Authentication**: User registration and login.
- **Roles and Permissions**: Assign roles to users and manage permissions.
- **API**: API endpoints for integration with other applications.

## Installation

Follow these steps to set up the project on your local machine:



**⁠Clone the Repository**:

```bash
git clone https://github.com/FabioMasciarelli/project-manager.git
```
```bash
cd project-manager
```


**Install Dependencies**:

Run the following commands to install PHP and Node.js dependencies:

```bash
composer install
```
```bash
npm install
```


**Set Up the Environment**:

Copy the .env.example file to create a .env file:

cp .env.example .env


**Generate the application key**:

```bash
php artisan key:generate
```


**Database Configuration**:
Open the .env file and set your database credentials:

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```


**Run migrations to set up the database schema**:

```bash
php artisan migrate
```

**Compile the frontend assets**:

```bash
npm run build
```


**Start the Development Server**:
Start the application using Laravel’s built-in server:

```bash
php artisan serve
```

The application will be available at http://localhost:8000.



## Contributing

Contributions are **welcome**! If you’d like to contribute:
1.	Fork the repository.
2.	Create a new branch for your feature or bugfix.
3.	Submit a pull request with a clear description of your changes.



## License

This project is licensed under the **MIT License**.
