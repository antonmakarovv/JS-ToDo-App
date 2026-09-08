# JS Todo App

A simple web application for task management built with pure JavaScript using localStorage for data persistence.

## Features

- Create tasks with title, date, and description
- Edit existing tasks
- Delete individual tasks
- Bulk delete all tasks (Clear All)
- Automatic data saving to localStorage
- Protection against data loss when closing the form with unsaved changes
- Responsive design for mobile devices

## Technologies

- HTML5
- CSS3
- Vanilla JavaScript (ES6+)
- localStorage API

## Project Structure

```
JS-Todo-App/
├── index.html          # Main HTML page
├── JS-ToDo-App/
│   ├── script.js       # Application logic
│   └── styles.css      # Styles
└── README.md           # Documentation
```

## Installation and Usage

1. Clone the repository or download the project files
2. Open `index.html` in your browser

No additional dependency installation required.

## Usage

### Adding a Task

1. Click the **Add New Task** button
2. Fill in the fields:
   - **Title** (required) — task name
   - **Date** — due date
   - **Description** — task description
3. Click **Add Task**

### Editing a Task

1. Click the **Edit** button on the task card
2. Modify the desired fields in the opened form
3. Click **Update Task**

### Deleting a Task

Click the **Delete** button on the task card to remove it.

### Deleting All Tasks

Click the **Clear All** button to delete all tasks. The button appears when there is at least one task in the list.

## Data Storage

All tasks are saved in the browser's localStorage under the `data` key. Data is saved automatically when:
- Adding a new task
- Editing a task
- Deleting a task
- Bulk deleting tasks

Data persists between browser sessions.

## Browser Support

The application works in all modern browsers with ES6+ and localStorage API support.
