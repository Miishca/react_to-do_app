# React ToDo App

A simple ToDo application built with React and TypeScript. The app allows users to create, edit, complete, and remove tasks, as well as filter them by status. The state is persisted in the browser's `localStorage`.

![todoapp](./description/todoapp.gif)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview

This application is based on the popular ToDoMVC app and includes the following features:

- Adding new tasks
- Marking tasks as complete/incomplete
- Editing tasks inline
- Filtering tasks by `All`, `Active`, or `Completed`
- Removing individual tasks
- Clearing completed tasks
- Persisting tasks in `localStorage`

## Features

- **Create todos**: Users can add new tasks by typing in the input field and pressing `Enter`.
- **Edit todos**: Double-click a task to edit its title. Press `Enter` to save changes or `Esc` to cancel.
- **Toggle completion**: Mark a task as completed by clicking the checkbox next to it.
- **Filter todos**: Use the filter buttons to view all, active, or completed tasks.
- **Clear completed**: Remove all completed tasks with one click.
- **LocalStorage**: Todos are saved automatically in the browser’s `localStorage` so the list is retained after page reloads.

## Technologies Used

- **React** (with TypeScript)
- **Context API** for state management
- **HTML/CSS** for layout and styling
- **LocalStorage** for data persistence

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   git clone https://github.com/<your_account>/react_to-do_app.git

2. Navigate to the project folder:
   cd react_to-do_app

3. Install the dependencies:
   npm install

4. Start the development server:
   npm start

## Usage

Add tasks by typing in the input field and pressing Enter.
Double-click a task to edit its title.
Use the filter buttons to show all, active, or completed tasks.
Click the "Clear completed" button to remove completed tasks.
Contributing
Contributions are welcome! If you have any improvements, please create a pull request with a clear description of the changes.

## License
This project is open-source and available under the MIT License.
