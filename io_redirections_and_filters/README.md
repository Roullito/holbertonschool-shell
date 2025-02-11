<div align="center">
  <img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png" alt="Banner">
</div>

# Shell, I/O Redirections and Filters

## Table of Contents

- [Resources](#resources)
  - [Read or Watch](#read-or-watch)
  - [Man or Help](#man-or-help)
- [Learning Objectives](#learning-objectives)
  - [Shell, I/O Redirection](#shell-io-redirection)
  - [Special Characters](#special-characters)
  - [Other Man Pages](#other-man-pages)
- [Requirements](#requirements)
  - [General Requirements](#general-requirements)
- [More Info](#more-info)
- [Tasks](#tasks)
  - [0. Hello World](#0-hello-world)
  - [1. Confused smiley](#1-confused-smiley)
  - [2. Let's display a file](#2-lets-display-a-file)
  - [3. What about 2?](#3-what-about-2)
  - [4. Last lines of a file](#4-last-lines-of-a-file)
  - [5. I'd prefer the first ones actually](#5-id-prefer-the-first-ones-actually)
  - [6. Line #2](#6-line-2)
  - [7. It is a good file that cuts iron without making a noise](#7-it-is-a-good-file-that-cuts-iron-without-making-a-noise)
  - [8. Save current state of directory](#8-save-current-state-of-directory)
  - [9. Duplicate last line](#9-duplicate-last-line)
  - [10. No more javascript](#10-no-more-javascript)
  - [11. Don't just count your directories, make your directories count](#11-dont-just-count-your-directories-make-your-directories-count)
  - [12. What’s new](#12-whats-new)
  - [13. Being unique is better than being perfect](#13-being-unique-is-better-than-being-perfect)
  - [14. It must be in that file](#14-it-must-be-in-that-file)
  - [15. Count that word](#15-count-that-word)
  - [16. What's next?](#16-whats-next)
  - [17. I hate bins](#17-i-hate-bins)
  - [18. Letters only please](#18-letters-only-please)
  - [19. A to Z](#19-a-to-z)
  - [20. Without C, you would live in hiago](#20-without-c-you-would-live-in-hiago)
  - [21. esreveR](#21-esrever)
  - [22. DJ Cut Killer](#22-dj-cut-killer)

---

## Resources

### Read or Watch
- [Shell, I/O Redirection](https://www.gnu.org/software/bash/manual/html_node/Redirections.html)
- [Special Characters](https://tldp.org/LDP/abs/html/special-chars.html)

### Man or Help
- `echo`
- `cat`
- `head`
- `tail`
- `find`
- `wc`
- `sort`
- `uniq`
- `grep`
- `tr`
- `rev`
- `cut`
- `passwd (5)`

---

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### Shell, I/O Redirection
- What do the commands `head`, `tail`, `find`, `wc`, `sort`, `uniq`, `grep`, `tr` do
- How to redirect standard output to a file
- How to get standard input from a file instead of the keyboard
- How to send the output from one program to the input of another program
- How to combine commands and filters with redirections

### Special Characters
- What are special characters
- Understand what white spaces, single quotes, double quotes, backslash, comments, pipes, command separators, and tilde do and how to use them

### Other Man Pages
- How to display a line of text
- How to concatenate files and print on the standard output
- How to reverse a string
- How to remove sections from each line of files
- What is the `/etc/passwd` file and what is its format
- What is the `/etc/shadow` file and what is its format

---

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on **Ubuntu 20.04 LTS**
- All your scripts should be exactly two lines long (`$ wc -l <file>` should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script is doing
- **You are not allowed** to use `&&`, `||` or `;`
- **You are not allowed** to use `sed` or `awk`
- All your files must be executable

---

## More Info

- Read your `/etc/passwd` and `/etc/shadow` files.
- **Note:** You do not have to learn about `fmt`, `pr`, `du`, `gzip`, `tar`, `lpr`, `sed`, and `awk` yet.

---

## Tasks

Each task in this project consists of a shell script that performs a specific function. Below is the list of tasks along with their descriptions.

### 0. Hello World
Write a script that prints `"Hello, World"`, followed by a new line to the standard output.

### 1. Confused smiley
Write a script that displays `"(Ôo)'`.

### 2. Let's display a file
Display the content of the `/etc/passwd` file.

### 3. What about 2?
Display the content of `/etc/passwd` and `/etc/hosts`.

### 4. Last lines of a file
Display the last 10 lines of `/etc/passwd`.

### 5. I'd prefer the first ones actually
Display the first 10 lines of `/etc/passwd`.

### 6. Line #2
Write a script that displays the third line of the file `iacta`.

### 7. It is a good file that cuts iron without making a noise
Write a shell script that creates a file with a specific name and content.

### 8. Save current state of directory
Write a script that writes into the file `ls_cwd_content` the result of `ls -la`.

### 9. Duplicate last line
Write a script that duplicates the last line of the file `iacta`.

### 10. No more JavaScript
Write a script that deletes all `.js` files in the current directory and subdirectories.

### 11. Don't just count your directories, make your directories count
Write a script that counts the number of directories and sub-directories in the current directory.

### 12. What’s new
Create a script that displays the 10 newest files in the current directory.

### 13. Being unique is better than being perfect
Create a script that takes a list of words and prints only words that appear exactly once.

### 14. It must be in that file
Display lines containing the pattern `"root"` from the file `/etc/passwd`.

### 15. Count that word
Display the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`.

### 16. What's next?
Display lines containing `"root"` and the 3 lines after them in the file `/etc/passwd`.

### 17. I hate bins
Display all lines in `/etc/passwd` that do not contain the pattern `"bin"`.

### 18. Letters only please
Display all lines of `/etc/ssh/sshd_config` starting with a letter.

### 19. A to Z
Replace all characters `A` and `c` from input to `Z` and `e`, respectively.

### 20. Without C, you would live in hiago
Create a script that removes all letters `c` and `C` from input.

### 21. esreveR
Write a script that reverses its input.

### 22. DJ Cut Killer
Write a script that displays all users and their home directories, sorted by users based on `/etc/passwd`.

---

This document provides an overview of the tasks involved in shell I/O redirections and filters. Each script follows the project requirements and constraints as specified in the **General Requirements** section.
