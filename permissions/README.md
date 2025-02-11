<div align="center">
  <img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png" alt="Banner">
</div>

# Shell, Permissions

## Table of Contents

- [Resources](#resources)
  - [Read or Watch](#read-or-watch)
  - [Man or Help](#man-or-help)
- [Learning Objectives](#learning-objectives)
  - [Permissions](#permissions)
  - [Other Man Pages](#other-man-pages)
- [Requirements](#requirements)
  - [General](#general)
- [Tasks](#tasks)
  - [0. My name is Betty](#0-my-name-is-betty)
  - [1. Who am I](#1-who-am-i)
  - [2. Groups](#2-groups)
  - [3. New owner](#3-new-owner)
  - [4. Empty!](#4-empty)
  - [5. Execute](#5-execute)
  - [6. Multiple permissions](#6-multiple-permissions)
  - [7. Everybody!](#7-everybody)
  - [8. James Bond](#8-james-bond)
  - [9. John Doe](#9-john-doe)
  - [10. Look in the mirror](#10-look-in-the-mirror)
  - [11. Directories](#11-directories)
  - [12. More directories](#12-more-directories)
  - [13. Change group](#13-change-group)
  - [14. Owner and group](#14-owner-and-group)
  - [15. Symbolic links](#15-symbolic-links)
  - [16. If only](#16-if-only)


## Resources

### Read or Watch
- [Permissions](https://www.gnu.org/software/coreutils/manual/html_node/File-permissions.html)

### Man or Help
- `chmod`
- `sudo`
- `su`
- `chown`
- `chgrp`
- `id`
- `groups`
- `whoami`
- `adduser`
- `useradd`
- `addgroup`

---

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### Permissions
- What do the commands `chmod`, `sudo`, `su`, `chown`, `chgrp` do
- Linux file permissions
- How to represent each of the three sets of permissions (owner, group, and other) as a single digit
- How to change permissions, owner and group of a file
- Why can’t a normal user `chown` a file
- How to run a command with root privileges
- How to change user ID or become superuser

### Other Man Pages
- How to create a user
- How to create a group
- How to print real and effective user and group IDs
- How to print the groups a user is in
- How to print the effective user ID

---

## Requirements

### General
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on **Ubuntu 22.04 LTS**
- All your scripts should be exactly two lines long (`$ wc -l <file>` should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file, at the root of the folder of the project, describing what each script is doing
- **You are not allowed** to use backticks, `&&`, `||`, or `;`
- **You are not allowed** to use `sed` or `awk`
- All your files must be executable
- **Warning:** Tasks `3`, `13`, `14`, `15`, and `16` must be done inside the sandbox in order to be corrected by the checker.

---

## Tasks

### 0. My name is Betty
Create a script that switches the current user to the user `betty`.

- You should use exactly 8 characters for your command (+1 character for the new line).
- You can assume that the user `betty` will exist when we run your script.

**File:** `0-iam_betty`

---

### 1. Who am I
Write a script that prints the effective username of the current user.

**File:** `1-who_am_i`

---

### 2. Groups
Write a script that prints all the groups the current user is part of.

**File:** `2-groups`

---

### 3. New owner
Write a script that changes the owner of the file `hello` to the user `betty`.

**File:** `3-new_owner`

---

### 4. Empty!
Write a script that creates an empty file called `hello`.

**File:** `4-empty`

---

### 5. Execute
Write a script that adds execute permission to the owner of the file `hello`.

**File:** `5-execute`

---

### 6. Multiple permissions
Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello`.

**File:** `6-multiple_permissions`

---

### 7. Everybody!
Write a script that adds execution permission to the owner, the group owner, and the other users, to the file `hello`.

**File:** `7-everybody`

---

### 8. James Bond
Write a script that sets the permission to the file `hello` as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

**File:** `8-James_Bond`

---

### 9. John Doe
Write a script that sets the mode of the file `hello` to `-rwxr-x-wx`.

**File:** `9-John_Doe`

---

### 10. Look in the mirror
Write a script that sets the mode of the file `hello` the same as `olleh`'s mode.

**File:** `10-mirror_permissions`

---

### 11. Directories
Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.

**File:** `11-directories_permissions`

---

### 12. More directories
Create a script that creates a directory called `my_dir` with permissions `751` in the working directory.

**File:** `12-directory_permissions`

---

### 13. Change group
Write a script that changes the group owner to `school` for the file `hello`.

**File:** `13-change_group`

---

### 14. Owner and group
Write a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory.

**File:** `14-change_owner_and_group`

---

### 15. Symbolic links
Write a script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively.

**File:** `15-symbolic_link_permissions`

---

### 16. If only
Write a script that changes the owner of the file `hello` to `vincent` only if it is owned by the user `guillaume`.

**File:** `16-if_only`

---
