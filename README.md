# To-Do List Application

A simple command-line To-Do List application written in Python.

## Features

- Add tasks to your to-do list
- List all current tasks
- Remove tasks by their index
- Prevents adding empty tasks (bug-fix branch)

## Installation

Clone the repository:

```bash
git clone https://github.com/CS303-G2/To-Do-List-APP.git
cd To-Do-List-APP
```

## Usage

Run the application:

```bash
python todo.py
```

### Available Functions

- `add_task(task)`: Add a new task to the list
- `list_tasks()`: Display all tasks currently in the list
- `remove_task(index)`: Remove a task by its index number

## Example

```python
add_task("Finish Assignment")
list_tasks()
add_task("Buy Groceries")
list_tasks()
remove_task(1)
list_tasks()
```

## Development

The application was developed using the following branches:
- `main`: Core functionality
- `feature-1`: Added task removal functionality
- `bug-fix`: Fixed bug preventing empty tasks

## Contributors

- CS303-G2 Team

## License

[MIT](LICENSE)
