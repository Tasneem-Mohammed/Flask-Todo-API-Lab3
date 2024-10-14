## The Endpoints

### 1. Get all tasks
**GET** `/todos`

Retrieves a list of all todo items.

**Response:**
```json
[
  {
    "id": 1,
    "title": "Go shopping",
    "completed": false
  }
]
```

### 2. Create a new todo
**POST** `/todos`

adds a new item.

**Request Body:**
```json
{
  "title": "Assignment 1",
  "completed": false
}
```
**Response:**
```json
{
  "id": 2,
  "title": "Software Task 1",
  "completed": false
}

```

### 3. Update an existing task
**PUT** `/todos:id`

Updates a todo item by its ID.

**Request Body (JSON):**
```json
{
  "title": "Updated tassk",
  "completed": true
}
```
**Response:**
```json
{
  "id": 2,
  "title": "Updated task",
  "completed": true
}
```

### Delete a task
**DELETE** `/todos:id`

Deletes a tassk item by its ID.

**Response:**
Status `204 `
```json
{
}
```
https://www.postman.com/telecoms-engineer-89074507/swe-lab-tasks/collection/ey2k9jc/labrequirement1?action=share&creator=39005368
