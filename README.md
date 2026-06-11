# CLI_todo

# CLI Todo App 📝

A lightweight command-line Todo application built with Node.js that allows users to add and view tasks directly from the terminal. This project demonstrates the fundamentals of Node.js, user interaction through the `readline` module, and basic state management using JavaScript arrays.

## Features

✅ Add new tasks

✅ View all tasks

✅ Interactive terminal menu

✅ Beginner-friendly codebase

✅ Built using native Node.js modules

## Tech Stack

* Node.js
* JavaScript (ES Modules)
* Readline API

## Getting Started

### Prerequisites

Make sure you have Node.js installed:

```bash
node --version
```

### Clone the Repository

```bash
git clone https://github.com/Shivam-BugHunter/CLI_todo.git
cd CLI_todo
```

### Install Dependencies

This project uses only built-in Node.js modules, so no additional packages are required.

```bash
npm install
```

### Run the Application

```bash
node app.js
```

## How It Works

When the application starts, an interactive menu is displayed:

```text
1: Add a task
2: View tasks
3: Exit
```

### Add a Task

Select option:

```text
1
```

Example:

```text
Enter a Task: Complete Node.js Project
```

Output:

```text
Task added: Complete Node.js Project
```

### View Tasks

Select option:

```text
2
```

Output:

```text
Your todo List
1. Complete Node.js Project
2. Practice JavaScript
```

### Exit

Select option:

```text
3
```

Output:

```text
Good Bye
```

## Example Run

```text
1: Add a task
2: View tasks
3: Exit

Choose an option: 1
Enter a Task: Learn ES Modules
Task added: Learn ES Modules

Choose an option: 1
Enter a Task: Build CLI Projects
Task added: Build CLI Projects

Choose an option: 2

Your todo List
1. Learn ES Modules
2. Build CLI Projects

Choose an option: 3
Good Bye
```

## Project Structure

```text
CLI_todo/
│
├── app.js
├── package.json
└── README.md
```

## Concepts Demonstrated

* ES Modules (`import`)
* Node.js `readline` module
* Arrays
* Functions and callbacks
* Conditional logic
* Command-line interfaces (CLI)
* User input handling

## Future Enhancements

* Delete tasks
* Edit tasks
* Mark tasks as completed
* Save tasks to a file
* Persistent storage with JSON or database
* Task priorities
* Due dates
* Colored terminal output

## Repository

[CLI Todo App Repository](https://github.com/Shivam-BugHunter/CLI_todo?utm_source=chatgpt.com)

## Author

**Shivam**

GitHub: [Shivam-BugHunter](https://github.com/Shivam-BugHunter?utm_source=chatgpt.com)

## License

This project is licensed under the ISC License.
