# To-Do List App - API Plan

Name: AMREEN Shaikh
Task: Task (32)
## About this task

This task is only about planning. I did not write any server code. I went through what the To-Do List app needs to do and worked out which APIs we will need to build later, following REST rules.

The full plan is in my Google Doc:

https://docs.google.com/document/d/1ku0YGBndnl9kcer2xeczCt2H2HvWlxMv2Ae1saAgeMw/edit?usp=sharing

## APIs I planned

| What it does | Method | URL |
|---|---|---|
| Add a task | POST | /api/tasks |
| Get all tasks | GET | /api/tasks |
| Get one task | GET | /api/tasks/:id |
| Edit a task | PUT | /api/tasks/:id |
| Mark done / not done | PATCH | /api/tasks/:id |
| Delete a task | DELETE | /api/tasks/:id |
| Filter and search | GET | /api/tasks?status=pending&search=word |

## CRUD coverage

- Create: Add Task
- Read: Get All Tasks, Get One Task, Filter and Search
- Update: Edit Task, Mark as Done
- Delete: Delete Task

## Challenges I expect

- Making a unique id for every task
- Checking the data that comes from the frontend
- Keeping the tasks saved after the server restarts
- Handling ids that do not exist
- Not mixing up PUT and PATCH
- CORS errors between the React app and the server

The Google Doc has more detail on each of these, plus the request bodies, responses and the reasoning behind each API.

## Links

