# Todo List Application

A simple web-based Todo List application built with HTML, CSS, and JavaScript. This application allows users to add, display, and delete tasks, providing an easy way to manage daily activities.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Functionality](#functionality)
- [File Structure](#file-structure)

## Features

- **Add Todo Items**: Users can input a task name and a due date to create new todos.
- **Display Todo List**: The application displays the current list of todos with their due dates.
- **Delete Todo Items**: Users can remove tasks from the list.
- **Responsive Design**: The application is designed to work well on different screen sizes.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/todo-list.git
   cd todo-list
   ```
## Usage

### Adding a Todo

1 - Enter a name for your task in the Todo Name input field.

2 - Select a due date using the Due Date input.

3 - Click the Add button to add the task to your list.

### Deleting a Todo

- Click the Delete button next to any todo item to remove it from the list.

## Functionality

The application consists of the following key functions:
- `renderTodoList()`: Renders the current todo list to the DOM by generating HTML for each todo item.
- `addTodo()`: Retrieves the user input from the form fields, adds a new todo item to the list, and calls `renderTodoList()` to update the display.
- Event Listeners:
  - For adding todos, the application listens for clicks on the Add button.
  - For deleting todos, each item has its own delete button with an event listener that removes the specific todo when clicked.
  - 
## File Structure
```bash
todo-list/
├── index.html                # Main HTML file
├── styles/
│   └── todo.css              # CSS styles for the application
└── scripts/
    └── todo.js               # JavaScript file for application logic
```

