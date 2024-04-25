# Kanban Task Management Board Application

This tool is designed to streamline your project management process through an intuitive and responsive interface, allowing users to manage tasks efficiently across various boards. Whether you're at your desk or on the move, our application adapts seamlessly to fit your device's screen size, enhancing productivity wherever you work. Dive into our documentation to explore how you can leverage this application to optimize your workflows, manage tasks with ease, and enhance your team's collaboration.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Create, read, update, and delete boards and tasks
- Receive form validations when trying to create/edit boards and tasks
- Mark subtasks as complete and move tasks between columns
- Hide/show the board sidebar

Expected Behaviour:

- Boards
  - Clicking different boards in the sidebar will change to the selected board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Clicking in the dropdown menu "Edit Board" opens up the "Edit Board" modal where details can be changed.
  - Columns are added and removed for the Add/Edit Board modals.
  - Deleting a board deletes all columns and tasks and requires confirmation.
- Columns
  - A board needs at least one column before tasks can be added. If no columns exist, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal where columns are added.
- Tasks
  - Adding a new task adds it to the bottom of the relevant column.
  - Updating a task's status will move the task to the relevant column.

Bonus:

- The tasks can be dragged and dropped to a new column.

### Screenshot

![Screenshot](<./public/screenshots/Screen%20Shot%202023-03-29%20at%201.40.56%20PM%20(2).png>)
<br/>
Home Board
<br/>
![Screenshot](<./public/screenshots/ss2.jpg>)
<br/>
Add New Task
<br/>
![Screenshot](<./public/screenshots/ss3.jpg>)
<br/>
Add New Board
<br/>
![Screenshot](<./public/screenshots/ss4.jpg>)
<br/>
Login Page
<br/>

### Links

- Live Site URL: [link](https://kanban-task-management-react-tailwind.vercel.app/)

### Built with

- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- Drag and Drop API
- [React](https://reactjs.org/) - JS library
- [Redux](https://redux.js.org/) - State management tool

### Useful resources

- [Drag and Drop quick tutorial](https://www.youtube.com/watch?v=u65Y-vqYNAk)

## Author

- LinkedIn - [Harsh Vardhan Shukla](https://www.linkedin.com/in/harsh-vardhan-shukla-vit/)
