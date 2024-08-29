# Task-Management-CLI-Tool-
Here's a brief README file for the CLI Task Manager tool:

## Description

The **Task Manager CLI Tool** is a simple command-line interface (CLI) application that helps us manage our daily tasks. We can easily add, view, complete, and delete tasks. All tasks are stored in a **tasks.txt** file, ensuring that our task list persists between sessions.

## Features

- **Add Tasks**: Add new tasks to our task list.
- **View Tasks**: Display all the tasks in our task list.
- **Complete Tasks**: Mark tasks as completed, which removes them from the list.
- **Delete Tasks**: Permanently delete tasks from our list.

### Usage

To run the Task Manager CLI Tool, use the following command:

```sh
python task_manager.py
```

### Commands

Once the tool is running, we will be presented with an options menu:

1. **Add Task**
   - Prompts us to enter the task description.
   - Example: `Enter the task: Buy groceries`

2. **View Tasks**
   - Displays all current tasks with their corresponding number.

3. **Complete Task**
   - Prompts us to enter the task number to mark as complete.
   - Example: `Enter the task number to complete: 2`

4. **Delete Task**
   - Prompts us to enter the task number to delete.
   - Example: `Enter the task number to delete: 1`

5. **Exit**
   - Exits the tool.

### Example

```sh
Task Manager
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
Choose an option: 1
Enter the task: Buy groceries
Added task: Buy groceries
Task Manager
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
Choose an option: 2
1. Buy groceries
```

## File Structure

- `CODE`: The file which contains main script that runs the CLI Task Manager.
- `tasks.txt`: The file where all tasks are stored.

