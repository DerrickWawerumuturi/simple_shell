# Simple Shell

🚀 **A Milestone Project in C Programming**  

---

## **Overview**

This project is a custom implementation of a simple UNIX shell, created as part of the ALX Africa Software Engineering program. The project serves as an introduction to advanced programming concepts such as process management, system calls, file handling, error handling, and more. The shell replicates the basic functionalities of the Thompson Shell.

---

## **Features**

- **Interactive Prompt:** Displays a prompt and waits for user input, ensuring each command ends with a newline.
- **Error Handling:** Prints an error message if an executable cannot be found, then re-displays the prompt.
- **End-of-File Handling:** Supports handling of the `Ctrl+D` EOF condition.
- **Command Line Arguments:** Accepts and processes commands with arguments.
- **PATH Resolution:** Locates executables using the `PATH` environment variable.
- **Exit Command:** Supports the `exit` command with optional exit status.
- **Signal Handling:** Prevents termination of the shell with `Ctrl+C`.
- **Command Separators:** Handles command separators (`;`).
- **Logical Operators:** Implements logical operators (`&&` and `||`).
- **Variable Replacement:** Handles variable replacements, including `$?` (last command status) and `$$` (process ID).
- **Comments:** Supports comments using the `#` character.
- **Command History:** Maintains a history of commands.
- **File Input:** Allows command input from files.

---

## **Built-in Commands**

| Command            | Description                                           |
|--------------------|-------------------------------------------------------|
| `exit [n]`         | Exits the shell, optionally with status `n`.          |
| `env`              | Prints the environment variables.                    |
| `setenv [var][value]` | Sets an environment variable with a value.         |
| `unsetenv [var]`   | Removes an environment variable.                     |
| `alias [name[='value']]` | Reads or sets an alias.                        |
| `cd [dir]`         | Changes the current directory.                       |
| `help [built-in]`  | Displays documentation for a built-in command.       |

---

## **Environment**

The shell was built and tested on **Ubuntu 14.04 LTS**.

---

## **Installation**

To install and use the shell, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/StellahMbao/simple_shell.git
   ```

2. Compile the source files:
   ```bash
   gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
   ```

3. Run the shell:
   ```bash
   ./hsh
   ```

---

## **Usage**

- Example command:
  ```bash
  ls -la
  ```
- Output:
  ```
  drwxr-xr-x 2 user user 4096 Jan 21 12:34 .
  drwxr-xr-x 3 user user 4096 Jan 21 12:34 ..
  -rw-r--r-- 1 user user 1234 Jan 21 12:34 file.txt
  ```

---

## **Contributors**

- **Derrick Muturi**  
- **Felix Kamue**

---

## **Acknowledgments**

- The creators of the C programming language.  
- Betty Holberton | ALX Africa.  
- Our Software Engineer-in-Residence for guidance and support.

---

## **License**

**Copyright (C) 2022 by Derrick Muturi and Felix Kamau. All rights reserved.**
