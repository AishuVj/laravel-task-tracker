
# Laravel Task Tracker

A simple and elegant task tracking web application built with Laravel and Bootstrap.  
This project demonstrates full CRUD functionality with database migrations, validation, and modern, responsive UI styling.

## Features

- Create, read, update, and delete tasks
- Mark tasks as completed with a checkbox
- Form validation with user-friendly error messages
- Responsive design powered by Bootstrap 5
- Uses SQLite by default for a lightweight database (easy to switch to MySQL or others)

## Screenshots

![Create Task] (images/image2.png)
![Edit Task] (images/image1.png)
 
## Getting Started

### Prerequisites

- PHP >= 8.x  
- Composer  
- SQLite (or MySQL if preferred and configured)  
- Node.js and npm (optional, if adding frontend assets)

### Installation

1. Clone the repository:

git clone https://github.com/AishuVj/laravel-task-tracker.git

cd laravel-task-tracker



2. Install PHP dependencies:

composer install



3. Create an environment file from the example:

cp .env.example .env



4. Generate an application key:

php artisan key:generate



5. Create the SQLite database file:

touch database/database.sqlite



6. Run database migrations:

php artisan migrate



7. Start the server:

php artisan serve



8. Access the app at `http://localhost:8000/tasks`

## Usage

- Use the user interface to create new tasks, edit them, mark completion, and delete as needed.
- Validation errors will be shown for required fields.
- Tasks are stored locally in the SQLite database.

## Contributing

Feel free to open issues or submit pull requests to enhance the project.

## License
This project is open source and available under the MIT License.




