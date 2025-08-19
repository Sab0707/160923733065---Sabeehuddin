This Spring Boot application provides a simple REST API for managing tasks. It includes the following components:

🔹 Components:

Task Model: Represents a task with fields for id, title, description, and status (as a string).

Status Enum: Defines valid task statuses (TODO, IN_PROGRESS, COMPLETED, BLOCKED).

TaskService: A service class using an in-memory HashMap to store and manage tasks. Supports basic CRUD operations.

TaskController: A REST controller that exposes endpoints to:

Create a task (POST /tasks)

Get a task by ID (GET /tasks/{id})

Get all tasks (GET /tasks)

Update a task (PUT /tasks/{id})

Delete a task (DELETE /tasks/{id})
