# Rails Task Manager

## Background & Objectives

This project is a basic To Do Manager built using Ruby on Rails. The Task Manager provides essential CRUD features, allowing users to create, read, update, and delete tasks. Through this challenge, you will practice using Rails' Active Record, the built-in Object-Relational Mapping (ORM) tool, to interact with the database efficiently.

## Features

* Task Listing: Users can view a list of all tasks.
* Task Details: Users can view detailed information for each task, including title and description.
* Add New Task: Users can create new tasks with a title and description.
* Edit Task: Users can edit existing tasks, update their title and details, or mark them as completed.
* Delete Task: Users can remove tasks from the list.

## User Stories

* List Tasks: As a user, I can view a list of all my tasks.
* View Task Details: As a user, I can view the details of a specific task.
* Add New Task: As a user, I can create a new task.
* Edit Task: As a user, I can mark a task as completed or update the task's title and details.
* Delete Task: As a user, I can remove a task from the list.

## Stack

* Ruby on Rails: Backend framework for handling routing, database interactions, and server-side logic.
* Active Record: ORM for handling database queries and managing task data.
* HTML/CSS: Frontend layout and styling for the views.

## Folder Structure

* app/: Contains the core application files including models, controllers, and views.
* controllers/: Handles requests and renders the appropriate views for listing, creating, updating, and deleting tasks.
* models/: Contains the Task model that handles interactions with the database using Active Record.
* views/: Contains the HTML templates for rendering the user interface (task list, form for adding/editing tasks, etc.).
* config/: Contains routing configuration and environment settings.
* db/: Contains migrations for creating and updating the database schema.

## Key Concepts

* CRUD Operations: The project implements the four key operations for tasks:
* Create: Add new tasks to the list.
* Read: Display tasks and their details.
* Update: Edit a task’s title or mark it as completed.
* Delete: Remove tasks from the list.
* Active Record: You will use Rails’ ORM, Active Record, to create and manage tasks, handling the database interactions in an easy and Rails-native way.

## How to Set Up the Project

1. Clone the repository:

```
git clone https://github.com/yourusername/rails-task-manager.git
cd rails-task-manager
```

2. Install dependencies:

```
bundle install
```

3. Set up the database:

```
rails db:create
rails db:migrate
```

4. Run the application:

```
rails server
```
Navigate to http://localhost:3000 to access the Task Manager.

## Future Enhancements

* Task Categories: Add support for categorizing tasks (e.g., work, personal).
* Due Dates: Implement functionality to assign and display due dates for tasks.
* Task Priorities: Introduce a priority system for tasks (e.g., high, medium, low).
* User Authentication: Add user accounts so each user can manage their own tasks.

## Contributions

This is a learning project, and contributions are welcome! Feel free to open an issue or submit a pull request to improve the Task Manager.

