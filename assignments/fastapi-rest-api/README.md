# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API with FastAPI that manages a small collection of tasks. You will practice defining routes, validating request data, returning appropriate HTTP status codes, and testing API behavior.

## 📝 Tasks

### 🛠️ Create the Task API

#### Description
Create a FastAPI application for managing tasks. Store tasks in memory so you can focus on the API rather than setting up a database.

#### Requirements
Completed program should:

- Start a FastAPI application that can be run with Uvicorn
- Define a task model with a unique ID, a title, and a description
- Implement `GET /tasks` to return all tasks and `POST /tasks` to create one
- Return the newly created task with HTTP status code `201`


### 🛠️ Add CRUD Routes and Validation

#### Description
Extend the API so a client can retrieve, update, and delete an individual task. Make sure the API responds clearly when a task cannot be found or request data is invalid.

#### Requirements
Completed program should:

- Implement `GET /tasks/{task_id}`, `PUT /tasks/{task_id}`, and `DELETE /tasks/{task_id}`
- Return HTTP status code `404` when a requested task does not exist
- Validate task input, including requiring a non-empty title
- Return an appropriate success status for updates and `204` for successful deletions


### 🛠️ Test the API

#### Description
Write automated tests for the task API using FastAPI's `TestClient`. Check both successful requests and common error cases.

#### Requirements
Completed program should:

- Test listing, creating, retrieving, updating, and deleting tasks
- Verify that creating a task returns status code `201` and the expected task data
- Verify that a missing task returns `404` and an invalid title is rejected
- Run the tests successfully from the command line
