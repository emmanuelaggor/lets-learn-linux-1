# 🐧 Let's Learn Linux - Assignment 1
fParoCyberDevSecOps Bootcamp**
 
---
 
## 📋 Overview
 
This repository contains my completed work for the **LetsLearnLinux1** assignment from the ParoCyber DevSecOps Bootcamp, facilitated by **Samuel Nartey**.
 
The assignment simulates a real first day at a DevSecOps job - setting up a deployment environment, writing and managing log files, working with hard and soft links, and understanding Linux data streams and redirection.
 
---
 
## 🗂️ Repository Structure
 
```
lets-learn-linux-1/
├── answers.md          ← Written answers to all 21 questions
├── screenshots/        ← Terminal screenshots for each task
└── README.md           ← You are here
```
 
---
 
## 📚 Sections Covered
 
| Section | Topic | Marks |
|---------|-------|-------|
| Section 1 | Orient Yourself - `pwd`, `whoami`, `uname`, FHS | 10 |
| Section 2 | Build the Environment - `mkdir`, `touch`, `tree` | 15 |
| Section 3 | Write and Read Files - `echo`, `cat`, heredoc, pagers | 20 |
| Section 4 | Move and Clean Up - `cp`, `mv`, `rmdir`, `rm` | 10 |
| Section 5 | Links and Inodes - hard links, soft links, inode table | 20 |
| Section 6 | Data Streams and Redirection - stdin, stdout, stderr | 15 |
 
---
 
## 🛠️ Tools and Commands Used
 
- `pwd`, `whoami`, `uname -a`
- `ls`, `ls -la`, `ls -li`, `tree`
- `mkdir -p`, `touch`, `cp`, `mv`, `rm`, `rmdir`
- `echo`, `cat`, `tac`, `more`, `less`, `tail`
- `ln`, `ln -s`
- Heredoc (`<< EOF`)
- Stream redirection (`>`, `>>`, `2>`, `2>&1`)
---
 
## 💡 Key Takeaways
 
- A filename is just a pointer to an inode - deleting a file doesn't destroy data if hard links still exist
- `stderr` (stream 2) and `stdout` (stream 1) are separate - always think about where errors are going in scripts
- Brace expansion + `mkdir -p` can build an entire directory tree in one command
- A quoted heredoc (`<< 'EOF'`) treats content as literal text; unquoted expands variables
---
 
## 👤 Author
 
**Emmanuel Selasie Aggor**
BSc Information Technology - University of Cape Coast, Ghana
Cybersecurity & DevSecOps Enthusiast
 
---
 
*This assignment is part of the DevSecOps training organised by @Parocyber and facilitated by @Samuel Nartey .*
