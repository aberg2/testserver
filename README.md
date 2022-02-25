# Instruktioner

# Respresentational state transfer - REST

HTTP method för att prata med webbservern.

```
BASE URL /tasks
GET / - Get all tasks
POST / - Create a new task
GET /:id - Get a task by id
PUT /:id - Update a task by id
DELETE /:id - Delete a task by id
```

# Create, Read, Update, Delete - CRUD

SQL
```
read - select
create - insert
update - update
delete - delete
```

# dotenv filer

Spara inte känslig data på git

.env filer är för detta, ladda aldrig upp på git
använd .gitignore
ladda dock upp en .env-example med info om vad som finns i .env