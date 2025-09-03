# Task Management Application

This repository contains a task management application built with Next.js, TypeScript, Tailwind CSS, and MST (Mobx State Tree). The application allows users to create, view, update, and delete tasks. It incorporates the specified technologies and follows best practices in terms of code organization, styling, and version control.

## Features

The task management application provides the following features:

- View a list of tasks
- Add a new task
- Edit an existing task
- Delete a task

Each task has the following properties:

- Title: A brief title describing the task
- Description: A detailed description of the task
- Status: The current status of the task (e.g., "To Do," "In Progress," "Completed")

The application implements CRUD (Create, Read, Update, Delete) operations on tasks and persists the task data using local storage.

## Getting Started

To run the task management application locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Ritabrata-Paul/Task-Management-Application.git
   ```

2. Navigate to the project directory:

   ```bash
   cd task-management-app
   ```

3. Install the dependencies:

   ```bash
   yarn
   ```

4. Run the development server:

   ```bash
   yarn run dev
   ```

5. Open your browser and visit [http://localhost:3000](http://localhost:3000) to see the application.

## Code Structure and Best Practices

The codebase is organized in a modular and maintainable manner. It follows best practices for code organization and project structure, ensuring code readability and maintainability through proper naming conventions, comments (where necessary), and code formatting.

The application also implements error handling and validation as appropriate.

## Version Control

Git version control is used for this project. The repository was initialized with a Git repository, and changes were committed at appropriate milestones. Git branches, commits, and pull requests were used to demonstrate an understanding of version control.

## Website Link

The application is deployed on Vercel. You can access it by visiting [Task Management Application](https://task-management-application-ritabrata.vercel.app/).

## Repository Link

The project repository can be found at [https://github.com/Ritabrata-Paul/Task-Management-Application](https://github.com/Ritabrata-Paul/Task-Management-Application).

## Error Handling and Validation

The application implements error handling and validation as appropriate. It ensures that users provide necessary information when creating or updating a task and displays appropriate error messages if any required field is missing or invalid.

## Future Improvements

Although the current implementation meets the basic requirements, there are several potential areas for future improvements, including:

- User authentication and authorization
- Backend integration for storing task data persistently
- Sorting and filtering options for task lists
- Drag-and-drop functionality for task organization
- User-friendly notifications and feedback

Feel free to contribute to the project by submitting pull requests or suggesting new features and improvements.

## License

This project is licensed under the [MIT License](LICENSE).
