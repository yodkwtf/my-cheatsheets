# Terminal Commands - A Cheatsheet to Basics

This cheat sheet is intended to be a quick refresher for the main concepts and commands involved in using a terminal. It is not a comprehensive guide, but should be enough to get the basics covered.

## What is Terminal?

The terminal is a text-based interface for interacting with your computer. It allows you to perform tasks that would be difficult or impossible to do using a graphical user interface. The terminal is also known as the _command line_, _shell_, or _console_.

#### Why Use Terminal?

- **Efficiency**: Many tasks can be performed more quickly using a terminal than using a graphical interface.
- **Automation**: You can write scripts to automate repetitive tasks.
- **Flexibility**: A terminal gives you more control over your system than a graphical interface.
- **Remote Access**: You can connect to remote servers using a terminal.
- **Hiring**: Many technical jobs require knowledge of a terminal.
- **Cool Factor**: Using a terminal makes you look like a hacker (even if you're not).

#### Terminal vs Command Line vs Shell

- **Terminal**: The terminal is the program that allows you to interact with a terminal. It provides a text-based interface for running commands.
- **Command Line**: a terminal is the text-based interface itself. It allows you to type commands and receive output.
- **Shell**: The shell is the program that interprets and executes your commands. There are many different shells available, but the most common one is `bash`.

## Some Keyboard Shortcuts

- **Ctrl + C**: Stop the current command and move to a clear new line.
- **Up/Down Keys**: Cycle through previous commands.
- **Tab Key**: Auto-complete file names and commands. Press twice to see all available options.
- **Ctrl + L**: Clear the terminal screen.
- **Ctrl + R**: Search through command history by typing a search term. It will show the most recent command that matches the search term.
- **Ctrl + D**: Exit the current shell.
- **q**: Quit out of a program that is running in the terminal.

## Basic Commands

The following are some of the most commonly used terminal commands:

- #### man [command]

  Used to show the manual/documentation for other commands.
  It shows all the available options, flags, and arguments for the command.

  ```sh
  man ls
  ```

  In Windows, `man` is not available. You can use `--help` instead.

  ```sh
  ls --help
  ```

- #### whoami

  Prints the username of the current user

  ```sh
  whoami # yodkwtf
  ```

- #### date

  Prints the current date and time.

  ```sh
  date # Fri 10 Dec 2021 10:00:00 AM IST
  ```

- #### clear

  Clears the terminal screen. Works same as `Ctrl + L`.

  ```sh
  clear
  ```
