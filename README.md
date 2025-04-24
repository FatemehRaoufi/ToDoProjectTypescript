# TypeScript Todo List

This is a simple **Todo List** application built with **TypeScript**. The app allows users to add tasks, mark them as completed, and remove completed tasks. It demonstrates the power of TypeScript in creating a modular and object-oriented application.

## Features

- Add new todos
- Toggle the state of todos (active/completed)
- Clear all completed todos
- Responsive UI powered by Bootstrap

## Project Structure

- `Model.ts`: Contains the definitions for `Todo` and `TodoState`.
- `TodoService.ts`: A service for managing todos (add, remove, toggle state).
- `TodoListComponent.ts`: Responsible for rendering todos on the UI.
- `TodoApp.ts`: Main class for handling the app logic and interaction between components.
- `index.html`: HTML file that serves as the interface.
- `styles.css`: Custom styles for the app.

## Installation

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/typescript-todo.git
   cd typescript-todo
Install dependencies: The project uses Bootstrap for UI and jQuery for DOM manipulation. You can include Bootstrap and jQuery via CDN in the index.html file, or you can install them locally with:

bash
Kopieren
Bearbeiten
npm install bootstrap jquery
Compile TypeScript: Make sure you have TypeScript installed on your system. If not, install it globally:

bash
Kopieren
Bearbeiten
npm install -g typescript
Then, run the TypeScript compiler:

bash
Kopieren
Bearbeiten
tsc
Open index.html: Open the index.html file in a web browser to see the app in action.

Usage
Once you have the app running, you can:

Add todos: Type a todo task and click "Add".

Toggle todos: Click on a todo to mark it as completed.

Clear completed: Click the "Clear Completed" button to remove all completed tasks.

