# Simplify Tasks

**Simplify Tasks** is a web-based task manager that helps you organize, track, and complete tasks effortlessly. It provides an easy-to-use interface to create tasks, view active tasks, delete tasks, and track completed tasks, helping you maintain productivity efficiently.

## Features

- **Create Tasks:** Add new tasks with a name, email, and target hours.
- **View Tasks:** See all active tasks with task number, name, description, and hours.
- **Delete Tasks:** Remove tasks permanently from your list.
- **Completed Tasks:** Mark tasks as completed and track them separately.
- **Progress Monitoring:** Automatically track counts of active, deleted, and completed tasks.

## Deployment

The project is deployed on Vercel:  
[Live Demo](https://your-vercel-url.vercel.app/)  

## Usage

1. Open the **Home Page (index.html)**.
2. Fill in your Name, Email, and Target Hours, then click **Submit**.
3. Navigate through the dashboard to create, view, delete, or complete tasks.
4. Monitor task counts to track your progress.

## Known Issues / Future Fixes

- **Negative Target Hours:** Currently, the target hours input allows negative numbers. Users are advised to enter positive numbers only.  
- Future updates will include **input validation** to prevent negative numbers automatically.  

## Notes

- All tasks are stored in the browser's **localStorage**; closing the browser resets data.
- Multi-page navigation uses relative paths to ensure smooth transitions.

## License

This project is free to use for personal, educational, or internship purposes.
