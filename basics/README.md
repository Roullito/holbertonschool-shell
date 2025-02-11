<div align="center">
  <img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png" alt="Banner">
</div>

# Shell, Basics

## Resources

### Read or Watch
- [What Is “The Shell”?](https://intranet.hbtn.io/rltoken/shell_overview)
- [Navigation](https://intranet.hbtn.io/rltoken/shell_navigation)
- [Looking Around](https://intranet.hbtn.io/rltoken/shell_looking_around)
- [A Guided Tour](https://intranet.hbtn.io/rltoken/shell_guided_tour)
- [Manipulating Files](https://intranet.hbtn.io/rltoken/shell_manipulating_files)
- [Working With Commands](https://intranet.hbtn.io/rltoken/shell_working_with_commands)
- [Reading Man Pages](https://intranet.hbtn.io/rltoken/shell_reading_man_pages)
- [Keyboard shortcuts for Bash](https://intranet.hbtn.io/rltoken/shell_keyboard_shortcuts)
- [LTS](https://intranet.hbtn.io/rltoken/shell_lts)
- [Shebang](https://intranet.hbtn.io/rltoken/shell_shebang)
- [Linux file systems explained](https://intranet.hbtn.io/rltoken/shell_filesystems)

### Man or Help
- `cd`
- `ls`
- `pwd`
- `less`
- `file`
- `ln`
- `cp`
- `mv`
- `rm`
- `mkdir`
- `type`
- `which`
- `help`
- `man`

---

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- What does RTFM mean?
- What is a Shebang?
- What is the Shell?
- What is the difference between a terminal and a shell?
- What is the shell prompt?
- How to use the history (the basics)?

### Navigation
- What do the commands `cd`, `pwd`, `ls` do?
- How to navigate the filesystem?
- What are the `.` and `..` directories?
- What is the working directory, how to print it and how to change it?
- What is the root directory?
- What is the home directory, and how to go there?
- What is the difference between the root directory and the home directory of the user `root`?
- What are the characteristics of hidden files and how to list them?
- What does the command `cd -` do?

### Looking Around
- What do the commands `ls`, `less`, `file` do?
- How do you use options and arguments with commands?
- Understand the `ls` long format and how to display it.

### A Guided Tour
- What does the `ln` command do?
- What do you find in the most common/important directories?
- What is a symbolic link?
- What is a hard link?
- What is the difference between a hard link and a symbolic link?

### Manipulating Files
- What do the commands `cp`, `mv`, `rm`, `mkdir` do?
- What are wildcards and how do they work?
- How to use wildcards?

### Working with Commands
- What do `type`, `which`, `help`, `man` commands do?
- What are the different kinds of commands?
- What is an alias?
- When do you use the command `help` instead of `man`?

### Reading Man Pages
- How to read a man page?
- What are man page sections?
- What are the section numbers for User commands, System calls, and Library functions?

### Keyboard Shortcuts for Bash
- Common shortcuts for Bash.

### LTS
- What does LTS mean?

---

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on **Ubuntu 22.04 LTS**
- All your scripts should be exactly two lines long (`$ wc -l <file>` should print `2`)
- All your files should end with a new line
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file at the root of the repo, containing a description of the repository.
- A `README.md` file, at the root of the folder of this project, describing what each script is doing.
- **You are not allowed** to use backticks, `&&`, `||`, or `;`
- **You are not allowed** to use `sed` or `awk`
- All your scripts must be executable.
- To make your file executable, use the `chmod` command: `chmod u+x filename`. Later, we’ll learn more about how to utilize this command.

---

## Tasks

### 0. Where am I?
Write a script that prints the absolute path name of the current working directory.

**File:** `0-current_working_directory`

---

### 1. What’s in there?
Display the contents list of your current directory.

**File:** `1-listit`

---

### 2. There is no place like home
Write a script that changes the working directory to the user’s home directory.

**File:** `2-bring_me_home`

---

### 3. The long format
Display current directory contents in a long format.

**File:** `3-listfiles`

---

### 4. Hidden files
Display current directory contents, including hidden files (starting with `.`), in long format.

**File:** `4-listmorefiles`

---

### 5. I love numbers
Display current directory contents with:
- Long format
- User and group IDs displayed numerically
- Hidden files (starting with `.`)

**File:** `5-listfilesdigitonly`

---

### 6. Welcome
Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

**File:** `6-firstdirectory`

---

### 7. Betty in my first directory
Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.

**File:** `7-movethatfile`

---

### 8. Bye bye Betty
Delete the file `betty` in `/tmp/my_first_directory`.

**File:** `8-firstdelete`

---

### 9. Bye bye My first directory
Delete the directory `my_first_directory` that is in the `/tmp` directory.

**File:** `9-firstdirdeletion`

---

### 10. Back to the future
Write a script that changes the working directory to the previous one.

**File:** `10-back`

---

### 11. Lists
Write a script that lists all files (including hidden ones) in the current directory, its parent, and `/boot/`, in long format.

**File:** `11-lists`

---

### 12. File type
Write a script that prints the type of the file named `iamafile` in `/tmp`.

**File:** `12-file_type`

---

### 13. We are symbols, and inhabit symbols
Create a symbolic link to `/bin/ls`, named `__ls__`, in the current working directory.

**File:** `13-symbolic_link`

---

### 14. Copy HTML files
Create a script that copies all `.html` files from the current working directory to its parent, but only if they are newer or do not exist in the parent.

**File:** `14-copy_html`

---

### 15. Let’s move
Move all files beginning with an uppercase letter to `/tmp/u`.

**File:** `15-lets_move`

---

### 16. Clean Emacs
Delete all files in the current working directory that end with `~`.

**File:** `16-clean_emacs`

---

### 17. Tree
Create directories `welcome/`, `welcome/to/`, and `welcome/to/school` in the current directory, using only **two** lines.

**File:** `17-tree`
