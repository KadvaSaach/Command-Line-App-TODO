# Todo App

This is a simple command-line todo application built with Python. It allows you to add, delete, update, mark as completed, and display tasks.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/KadvaSaach/Command-Line-App-TODO.git

2. Change into the project directory:
 
    ```shell
    cd Command-Line-App-TODO

3. Install the dependencies:

    ```shell
    pip -r requirements.txt

Available commands:

* `add`: Add a new task.
* `delete`: Delete a task by its position.
* `update`: Update the details of a task.
* `complete`: Mark a task as completed.
* `show`: Display all tasks.

## Add

To add a new task, use the `add` command followed by the task and category arguments:

```shell
    python main.py add "Buy groceries" "Shopping"
```

## Delete

To delete a task, use the `delete` command followed by the position argument:

```shell
    python main.py delete 2

```

This will delete the task at the specified position.

## Update

To update a task, use the `update` command followed by the position argument and the task or category arguments (or both):

```shell
    python main.py update 1 --task "Read a book"
```

This will update the task at the specified position with the new task value.

## Complete

To mark a task as completed, use the `complete` command followed by the position argument:

```shell
    python main.py complete 3
```

This will mark the task at the specified position as completed.

### Show

To display all tasks, use the `show` command:

```shell
    python main.py show
```

This will show a table with all the tasks, their categories, and their completion status.

