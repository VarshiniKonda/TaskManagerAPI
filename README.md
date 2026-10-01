# Task Manager REST API

A RESTful Task Manager API built using Django REST Framework with Token Authentication.

## Technologies Used

- Python
- Django
- Django REST Framework
- SQLite
- Postman
- Git & GitHub

## Features

- Create tasks
- View all tasks
- View a single task
- Update tasks
- Partially update tasks
- Delete tasks
- Token-based authentication
- Protected API endpoints

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/token/` | Generate authentication token |
| GET | `/api/tasks/` | List all tasks |
| POST | `/api/tasks/` | Create a task |
| GET | `/api/tasks/<id>/` | Get task details |
| PUT | `/api/tasks/<id>/` | Update a task |
| PATCH | `/api/tasks/<id>/` | Partially update a task |
| DELETE | `/api/tasks/<id>/` | Delete a task |

## Authentication

This API uses Token Authentication.

Add the following header to protected requests:

```text
Authorization: Token YOUR_TOKEN
## Docker Setup

### Prerequisites

- Docker Desktop installed and running

### Build the Docker Image

```bash
docker build -t taskmanagerapi .