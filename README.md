# Task Management App


## Table of Contents

- [Description](#description)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

## Description

The Task Management App is a web application built with Django and React that helps users manage their tasks and to-do lists efficiently. It provides an intuitive interface for creating, updating, and organizing tasks, making it easier to stay organized and productive.

## Features
- **Task Creation**: Easily create tasks with titles, descriptions, deadlines, and priority levels.
- **Task Lists**: Organize tasks into custom lists or categories.
- **Task Updates**: Edit and update task details as needed.
- **Task Deletion**: Delete completed or unnecessary tasks.
- **Responsive Design**: The app is responsive and works seamlessly on various devices.
- **Real-time Updates**: See changes and updates in real-time without page refresh using React.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Python**: Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

- **Node.js and npm**: You'll need Node.js and npm (Node Package Manager) for the React frontend. You can download them from [nodejs.org](https://nodejs.org/).

- **Django**: Install Django using pip:

  ```bash
  pip install django
  ```

Installation
1.Clone the repository:

```bash
git clone https://github.com/yourusername/task-management-app.git
```

2.Navigate to the project directory:

```bash
cd task-management-app
```


3.Install Python dependencies:

```bash
pip install -r requirements.txt
```

4.Navigate to the frontend directory and install React dependencies:

```bash
cd frontend
```



## Usage
1.Start the Django development server:

```bash
python manage.py runserver
```

The backend will be available at http://localhost:8000/.

2.In a separate terminal, start the React development server from the frontend directory:

```bash
npm start
```

The frontend will be available at http://localhost:3000/.

3 .Access the app in your web browser and register/login to start using it.

```bash
npm install
```

## Technologies Used
Django: A Python web framework for building the backend.

React: A JavaScript library for building the frontend user interface.

React Router: For handling client-side routing.

Django REST framework: To create a RESTful API for the frontend.

SQLite: A simple and lightweight database for development.

Axios: A promise-based HTTP client for making API requests.

JWT Authentication: JSON Web Tokens for secure user authentication.

Material-UI: A popular React UI framework for building the user interface.

Webpack: For bundling and managing frontend assets.

Babel: To transpile modern JavaScript to a compatible version.

ESLint: For code quality and style checks.

Git: Version control for collaborative development.
Contributing
