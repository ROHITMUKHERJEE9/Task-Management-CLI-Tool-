# Task-Management-CLI-Tool-
Here's a brief README file for your CLI Task Manager tool:

## Description

The **Task Manager CLI Tool** is a simple command-line interface (CLI) application that helps you manage your daily tasks. You can easily add, view, complete, and delete tasks. All tasks are stored in a `tasks.txt` file, ensuring that your task list persists between sessions.

## Features

- **Add Tasks**: Add new tasks to your task list.
- **View Tasks**: Display all the tasks in your task list.
- **Complete Tasks**: Mark tasks as completed, which removes them from the list.
- **Delete Tasks**: Permanently delete tasks from your list.

## Getting Started

### Prerequisites

- Python 3.x

### Installation

1. Clone the repository or download the script.

2. Ensure you have Python 3 installed on your system.

3. Navigate to the directory where the script is located.

### Usage

To run the Task Manager CLI Tool, use the following command:

```sh
python task_manager.py
```

### Commands

Once the tool is running, you will be presented with a menu of options:

1. **Add Task**
   - Prompts you to enter the task description.
   - Example: `Enter the task: Buy groceries`

2. **View Tasks**
   - Displays all current tasks with their corresponding numbers.

3. **Complete Task**
   - Prompts you to enter the task number to mark as complete.
   - Example: `Enter the task number to complete: 2`

4. **Delete Task**
   - Prompts you to enter the task number to delete.
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
Enter the task: Finish reading book
Added task: Finish reading book

Task Manager
1. Add Task
2. View Tasks
3. Complete Task
4. Delete Task
5. Exit
Choose an option: 2
1. Finish reading book
```

## File Structure

- `task_manager.py`: The main script that runs the CLI Task Manager.
- `tasks.txt`: The file where all tasks are stored. This file is automatically created in the same directory as the script.

## Acknowledgments

This tool was developed as a simple demonstration of how to create a basic CLI application in Python.
