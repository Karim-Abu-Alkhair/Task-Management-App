# React Task Management Application

This is a simple TODO application built with React that allows users to add, edit, complete, and delete tasks. The application uses `localStorage` to persist tasks across browser sessions.

## Features

- **Add Tasks**: Users can add new tasks with a unique identifier.
- **Complete Tasks**: Users can mark tasks as complete or incomplete.
- **Edit Tasks**: Users can edit the titles of existing tasks.
- **Delete Tasks**: Users can delete tasks from the list.
- **Persistent Storage**: Tasks are saved in `localStorage`, so they remain even after refreshing the page.

## Components

- **Home**: Main component that manages the state of tasks and renders the other components.
- **Header**: Displays the title of the application.
- **TODOHero**: Displays the number of completed tasks out of the total number of tasks.
- **Form**: A form for adding new tasks.
- **TODOList**: Displays the list of tasks with options to edit, complete, and delete each task.
- **Item**: Sub-component of `TODOList` for rendering individual task items with edit, complete, and delete functionality.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/react-todo-app.git
   ```

2. **Navigate into the project directory**:

   ```bash
   cd react-todo-app
   ```

3. **Install dependencies**:

   ```bash
   npm install
   ```

   or, if you are using yarn:

   ```bash
   yarn install
   ```

## Usage

1. **Start the development server**:

   ```bash
   npm start
   ```

   or, with yarn:

   ```bash
   yarn start
   ```

2. Open your browser and go to `http://localhost:3000` to view the application.

## Key Dependencies

- **React**: JavaScript library for building user interfaces.
- **uuid**: Library for generating unique identifiers.

## Saving and Loading Tasks

- **Saving**: When a task is added, edited, completed, or deleted, the updated task list is saved to `localStorage`.
- **Loading**: On application load, tasks are fetched from `localStorage` and displayed.
