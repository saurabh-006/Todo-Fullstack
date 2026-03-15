📝 Todo Fullstack Application

A simple Fullstack Todo Application built using ASP.NET Core Web API for the backend and Angular for the frontend.

The application allows users to create, view, update, and delete tasks (CRUD).

🚀 Tech Stack
Backend

ASP.NET Core

C#

Entity Framework Core

Local Microsoft SQL Server

Frontend

Angular

Bootstrap

Bootstrap Icons

TypeScript

📂 Project Structure
Todo-Fullstack
│
├── backend
│   └── TodoApi
│
└── frontend

✨ Features

Add new todo tasks

View all tasks

Update existing tasks

Delete tasks

Responsive UI using Bootstrap

Icon-based action buttons

🗄 Database

Database used: Local SQL Server

Model:

TodoItem
-------
Id (int)
Title (string)
IsCompleted (bool)
⚙️ Backend Setup

Open the backend project in Visual Studio

Configure database connection in:

appsettings.json

Run the API

API runs on:

https://localhost:7196/api/Todo
⚙️ Frontend Setup

Go to frontend folder:

cd frontend/todo-frontend

Install dependencies:

npm install

Run Angular app:

ng serve

Open in browser:

http://localhost:4200
🔗 API Endpoints
Method	Endpoint	Description
GET	/api/Todo	Get all todos
POST	/api/Todo	Create todo
PUT	/api/Todo/{id}	Update todo
DELETE	/api/Todo/{id}	Delete todo
👨‍💻 Author

Saurabh

📄 License

This project is for learning purposes.
