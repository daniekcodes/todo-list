# Todo App

This is a simple Todo application built with Next.js and Prisma.

## Prerequisites

Before running this application, make sure you have the following installed:

- Node.js
- npm or yarn
- PostgreSQL

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/todo-app.git
Install the dependencies:

bash
Copy code
cd todo-app
npm install
Set up the database:

Create a PostgreSQL database for the application.
Update the database connection configuration in the prisma/client file.
Start the development server:

bash
Copy code
npm run dev
Open your browser and navigate to http://localhost:3000 to see the application.

Usage
The homepage displays a list of todos.
Click on a todo to toggle its completion status.
Click on the "New" button to create a new todo.
Files
page.tsx: This file contains the main page component that displays the list of todos and handles toggling of todo items.

new/page.tsx: This file contains the component for creating a new todo.

Technologies Used
Next.js
Prisma
React
License
This project is licensed under the MIT License.
