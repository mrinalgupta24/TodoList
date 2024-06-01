# TodoList

## TODO List Application

### Description

A React-based To-Do List application that enables users to add, remove, and mark tasks as completed, with data persistence handled through localStorage.

### Features

- Add new tasks
- Mark tasks as completed/incomplete
- Edit tasks
- Delete tasks
- Persistent storage using localStorage
- Validate task input
- Display tasks dynamically


### Technologies Used

The application is built using the following technologies:

- React Js
- Node Js
- Mongo Db
- Google Auth
- Firebase

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/mrinalgupta24/TodoList.git
    cd my-todo-app
    ```

2. Install dependencies:
    ```bash
    npm i
    npm i uuid
    ```

3. Start the application:
    ```bash
    npm start
    ```

### Testing Guidance

1. **Add a Todo**: Enter a task and click "Add or Press Enter".
2. **Mark as Completed**: Click the green tick button to mark as completed.
3. **Edit a Todo**: Click the edit button next to a task to edit the task , it will show in the input of add task then the task can be saved again.
4. **Delete a Todo**: Click the delete button next to a task to delete a task (deletes directly!).
5. **LocalStorage**: Refresh the page to ensure tasks persist between sessions.
6. **Validate the input** : The Save button will not be in action if the input text has less than or equal to 3 characters.
