#  Todo List project

A dynamic to-do list application built with Node.js, Express, EJS, PostgreSQL, and styled with CSS. This app allows users to manage their tasks efficiently, including adding, editing, and deleting items from their list.
Table of Contents

    Features
    Prerequisites
    Setup Instructions
    Usage
    Scripts
    Screenshots
    Technologies Used
    License

Features

    Add new items to the to-do list.
    Edit existing tasks dynamically.
    Mark tasks as complete and delete them.
    Responsive design with a clean user interface.
    Backend powered by PostgreSQL for reliable data storage.

Prerequisites

Before running the project, ensure you have the following installed:

    Node.js (v14+ recommended)
    PostgreSQL (v12+ recommended)
    npm (Node Package Manager)

Setup Instructions
1. Clone the Repository
   git clone https://github.com/yourusername/permalist-project.git
   cd permalist-project

2. Install Dependencies
   npm install

3. Set Up Environment Variables
Create a .env file in the root directory with the following content:
  DB_USER=your_postgres_username
  DB_PASSWORD=your_postgres_password
  DB_HOST=localhost
  DB_NAME=permalist
  DB_PORT=5432

4. Create the Database
Run the SQL script in queries.sql to set up the database:
  psql -U your_postgres_username -d postgres -f queries.sql

5. Start the Server
Run the server using Nodemon:
  npx nodemon solution.js

6. Access the Application
Open your browser and visit:
  http://localhost:3000

