---
title: Git Version Control System
summary: Information about Git version control systems and commands
date: 2025-03-16
authors:
  - admin
tags:
  - Version Control
  - GitHub
image:
  caption: 'Image credit: [About Github](https://www.thurrott.com/cloud/278695/github-crosses-100-million-developers-milestone)'
---

Information about Git version control systems and commands

## What is it?

- The Git version control system is a set of command-line programs. They can be accessed from the terminal by entering the git command with various options.

- Due to the fact that Git is a distributed version control system, a backup copy of the local repository can be made by simply copying or archiving.

## Basic git commands:

For example, in the table. @tbl:std-dir provides a brief description of the main Git commands.

: Description of some Git version control system commands {#tbl:std-dir}

| Command | Description of the command                                                                                                        |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `git init`   | create the main repository tree                                                                                     |
| `git pull `  | get updates (changes) of the current tree from the central repository                                               |
| `git push`   | send all changes made to the local tree to the central repository                                          |
| `git status` | view a list of modified files in the current directory                                                                     |
| `git diff`   | view current changes                                                                                                 |
| `git add`    | file_names add specific modified and/or created files and/or directories                                           |
| `git rm`     | remove a file and/or directory from the repository index (while the file and/or directory remains in the local directory)            |
| `git rm имена_файлов`     | remove a file and/or directory from the repository index (while the file and/or directory remains in the local directory)            |
| `git commit -am 'Описание коммита'`     | Save all added changes with a comment using the built-in editor           |
| `git checkout -b имя_ветки`     | Create a new branch based on the current one            |
| `git branch -d имя_ветки`     | Delete a local branch that has already been merged into the main tree            |
| `git branch -D имя_ветки`     | Force deletion of a local branch            |

The full list of commands can be found on the official website  [Github.com](https://docs.github.com/en/get-started/using-github/github-command-palette)

