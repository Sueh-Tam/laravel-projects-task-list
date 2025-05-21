# Laravel Task List Application

## About the Project

This is a web application built with Laravel framework that allows users to efficiently manage their tasks. The application provides a complete task management system with the following features:

- **Create Tasks**: Users can create new tasks by providing a title, description, and optional detailed description.
- **View Tasks**: Users can view a list of all tasks and access detailed information about each task.
- **Edit Tasks**: Users can modify existing tasks by updating their title, description, or detailed description.
- **Delete Tasks**: Users can remove tasks from the database when they are no longer needed.
- **Mark as Complete**: Users can toggle the completion status of tasks to track their progress.

The application features a clean, user-friendly interface and implements Laravel's best practices for web development.

## How to Build the Project

To build this project, you will need to have PHP and MySQL installed on your machine.

### Configuration Steps:

1. Copy the file named **.env.example** and paste it, rename the file to **.env**, and make these changes:
   - Set your database name in `DB_DATABASE=`
   - Set your database username in `DB_USERNAME=`
   - Set your database password in `DB_PASSWORD=`

### Installation Commands:

Run the following commands in the main project directory:

1. **composer install**
2. **composer dump-autoload**
3. **php artisan config:clear**
4. **php artisan cache:clear**
5. **php artisan migrate**
6. **php artisan db:seed**
7. **php artisan serve**

After running these commands, the application will be available at http://localhost:8000.
