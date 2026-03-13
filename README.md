Task Flow
A task management web application built with vanilla JavaScript as part of a Web Technology course assignment.

Live Demo
https://sufiyan-shaik.github.io/TaskFlow-/.

About
This app lets you create, manage and organize tasks by category and priority. Built using plain HTML, CSS, and JavaScript — no frameworks or libraries used (except Font Awesome for icons).

Features
Create, Edit, Delete tasks — full CRUD operations
Task details — each task has a title, description, priority (low/medium/high), and category
Categories — organize tasks into Personal, Work, Urgent, or Other
Filter tasks — filter by category, priority, or completion status
Sort tasks — sort by newest, oldest, priority, or title
Search — search tasks by title or description
Mark as Complete — completed tasks get a strikethrough style
Priority Notifications — alerts pop up when a high-priority task is added, updated, or completed. They disappear automatically after 4 seconds
Dark / Light Theme — toggle between dark and light mode, preference is saved
Responsive Design — works on desktop and mobile screens
Data Persistence — tasks are saved in the browser's localStorage so they stay after refreshing


OOP Design
The app is built using two JavaScript classes:
Task class — represents a single task with properties:
`id`, `title`, `description`, `priority`, `category`, `completed`, `createdAt`
Methods: `complete()`, `update()`, `getAge()`
TaskFlow class — handles all operations:
`add()`, `update()`, `delete()`, `toggle()`, `getById()`, `filter()`, `sort()`, `getCounts()`
Reads and writes to localStorage

Validation
Title is required and must be at least 3 characters
Priority and Category must be selected
Error messages are shown inline under each field

Tech Stack
HTML5
CSS3 (CSS variables, flexbox, grid, media queries, animations)
Vanilla JavaScript (ES6 classes, DOM manipulation, localStorage)
Font Awesome 6 (icons via CDN)

How to Run Locally
Just open `index.html` in any browser. No server or setup needed.

Project Structure
```
task-flow/
└── index.html      (entire app — HTML, CSS, and JS in one file)
```
Screenshots
> Dark mode — task grid view
> Light mode — add task modal

Author
Sufiyan Shaik
