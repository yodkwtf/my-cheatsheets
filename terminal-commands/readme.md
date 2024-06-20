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

  Prints the username of the current user.

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

## File System Navigation

The following commands are used to navigate around the file system:

- #### pwd

  Prints the current working directory.

  ```sh
  pwd # /home/yodkwtf
  ```

  If you see `~` in the path, it represents the home directory.

- #### ls [dirname]

  Lists the files and directories within a directory. By default, it lists the files in the current directory.

  ```sh
  ls
  ```

  To list files in a specific directory, provide the directory name as an argument.

  ```sh
  ls /path/to/directory
  # ls /Downloads/
  ```

  To list all files (including hidden files), use the `-a` flag.

  ```sh
  ls -a
  ```

  To list files with more details (size, permissions, etc.), use the `-l` flag.

  ```sh
  ls -l
  ```

  To reverse the order of the list, use the `-r` flag.

  ```sh
  ls -r
  ```

  We can also combine flags.

  ```sh
  ls -ra # hidden files will be at the bottom
  ```

  There are many more flags available. You can check the manual for more information.

- #### cd [dirname]

  Changes the current directory to the specified directory.

  ```sh
  cd /path/to/directory
  # cd /Downloads/
  ```

  To go to the home directory, use `cd` without any arguments.

  ```sh
  cd
  ```

  Or use `cd ~`.

  ```sh
  cd ~
  ```

  To go to the last directory you were in, use `cd -`.

  ```sh
  cd -
  ```

  To go up one directory, use `cd ..`.

  ```sh
  cd ..
  ```

  To go to the root directory of the machine, use `cd /`.

  ```sh
  cd /
  ```

- #### open [file/folder]

  To open files, there are different commands based on the operating system.

  On MacOS, you can use `open`.

  ```sh
  open filename.txt
  open Downloads/
  ```

  On Linux, you can use `xdg-open`.

  ```sh
  xdg-open filename.txt
  xdg-open Downloads/
  ```

  On Windows, you can use `start`.

  ```sh
  start filename.txt
  start Downloads/
  ```

  We can also open URLs using the same command.

  ```sh
  open https://yodkwtf.com
  ```
