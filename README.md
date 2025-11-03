# My Advanced C Shell

This is a custom Unix-like command-line shell developed in C. It provides essential shell functionality, including program execution, I/O management, job control, and several custom built-in commands.

## ✨ Features

* *Core Execution:* Execute external programs available in your system's PATH.
* *Built-in Commands:* Includes cd, pwd, echo, history, env, set, unset, jobs, kill, help, and exit.
* *I/O Redirection:* Supports input (<), output overwrite (>), and output append (>>).
* **Piping (|):** Connects the output of one command to the input of the next.
* *Background Jobs:* Run tasks in the background using the ampersand (&).
* *Job Control:* Use jobs to view background processes and kill PID to terminate them.
* *History:* Tracks recently entered commands using the history built-in.

## 🚀 Getting Started

### Prerequisites

You need a standard C compiler (like *GCC*) and a Unix-like operating system (Linux, macOS, or WSL).

### Compilation

Since the shell is consolidated into a single file (myshell.c), you can compile it using GCC:

```bash
gcc -o myshell myshell.c
