# Task Tracker React App

A simple React application to manage daily tasks. This app allows users to add, view, edit, and delete tasks with features like inline editing and local storage for data persistence.

## Features

- **Add Task**: A form to add a new task with fields for Title, Description, Due Date, and Status (Pending, In Progress, Completed).
- **View Tasks**: Displays tasks in a table or cards for easy viewing.
- **Edit Task**: Inline or modal-based editing of existing tasks.
- **Delete Task**: Remove tasks with a confirmation prompt.
- **State Management**: Uses `useState` for local state management.
- **Styling**: Responsive design using plain CSS or a framework like Bootstrap/Tailwind.
- **Data Persistence**: Stores tasks in the browser's local storage.

### Bonus Features
- Filters tasks by status.
- Sorts tasks by due date.
- Utilizes `useContext` or Redux for advanced state management.

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Kondapaneni/Task-Tracker.git
   cd task-tracker
   
2. Install dependencies:
   ```bash
   npm install
   
3. Start the development server:
   ```bash
   npm run dev
   
4. Open the app in your browser:
   ```bash
   http://localhost:3000

## How It Works
1, Add a Task:
  - Use the "Add Task" form to create new tasks.
  - Enter the Title, Description, Due Date, and Status.
  
2, View Tasks:
  - Tasks are displayed in a responsive table or card layout.

3, Edit a Task:
  - Click the edit button on a task to update its details.
  
4, Delete a Task:
  - Click the delete button and confirm the action to remove a task.

5, Local Storage:
  - All tasks are stored in the browser's local storage, ensuring they persist between sessions.

## Future Enhancements
- Authentication: Add user authentication to save tasks for specific users.
- Backend Integration: Connect to a database for persistent storage across devices.
- Mobile App: Build a mobile version of the app using React Native.


