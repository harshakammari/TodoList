# ToDoList Web Application

This repository contains the source code for a simple and elegant To-Do List web application. The application allows users to add, remove, and mark tasks as completed in a visually appealing and user-friendly interface.

## Table of Contents
- [Files](#files)
- [HTML Structure](#html-structure)
- [CSS Styling](#css-styling)
- [JavaScript Functionality](#javascript-functionality)
- [Summary](#summary)

## Files
- **index.html**: Defines the structure and content of the web page.
- **style.css**: Provides styling for the web page elements.
- **script.js**: Implements the dynamic functionality of the To-Do List.

## HTML Structure
### `<head>`
- **Meta Tags**: Ensures proper rendering and scaling on various devices.
- **Title**: Sets the title of the web page.
- **Stylesheets**: Links the external CSS file and Font Awesome for icons.

### `<body>`
- **Container**: Wraps the entire content for styling purposes.
- **ToDo App Section**: Contains the To-Do List application.
  - **Header (h2)**: Displays the title along with an icon.
  - **Input Row (div.row)**: Consists of an input box and an "Add" button.
  - **Task List (ul#list-container)**: Container for dynamically added tasks.

## CSS Styling
- **Global Styles (body)**: Sets the background color for the entire page.
- **ToDo App Styles (.todo-app)**: Defines the background, border radius, box shadow, and padding for the ToDo App.
- **Animation Styles (@keyframes)**: Adds subtle animations for a smoother appearance.
- **Header Styles (h2)**: Uses flexbox for alignment, color, and fadeInLeft animation.
- **Input Styles (input)**: Styles the input box with transitions for a smooth border color change on focus.
- **Button Styles (button)**: Defines the styles for the "Add" button with hover effects.
- **Task List Styles (ul, li)**: Specifies the styles for the task list items, including background, padding, border radius, and box shadow.
- **Checked Task Styles (.checked)**: Styles for the completed tasks with a line-through effect.

## JavaScript Functionality
- **Event Listener**: Listens for clicks on the task list to toggle task completion and remove tasks.
- **addTask Function**: Adds a new task to the list, ensuring the input is not empty.
- **saveData Function**: Saves the current state of the task list to local storage.
- **showTask Function**: Retrieves and displays tasks from local storage on page load.

## Summary
This To-Do List web application combines HTML, CSS, and JavaScript to create a visually appealing and functional task management tool. The HTML defines the structure, CSS provides styling, and JavaScript handles dynamic functionality such as adding, marking, and removing tasks. The application incorporates animations for a smoother user experience, and local storage ensures persistent data across page reloads. The code is well-organized and follows best practices for maintainability and readability. Feel free to explore and customize this application for your task management needs!
