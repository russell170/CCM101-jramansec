# Laboratory 01 – Welcome to the Cloud

## Mission Overview

This laboratory introduces the fundamentals of working with a
cloud-based Linux environment. The mission involves exploring
Ubuntu through the command line, managing users, collecting
system information, organizing files, and documenting the
activities performed during the laboratory.

## Objectives

- Access and navigate a cloud-based Ubuntu Linux environment.
- Practice basic Linux terminal commands.
- Create and manage a Linux user account.
- Configure administrative privileges using the sudo group.
- Gather information about the operating system and hardware.
- Create and organize laboratory files and directories.
- Document the laboratory activities using Markdown.
- Prepare the laboratory work for submission through GitHub.

## Activities Performed

1. Accessed the Ubuntu environment using KillerCoda.
2. Checked the current Linux user using `whoami`.
3. Checked the current working directory using `pwd`.
4. Identified the hostname using `hostname`.
5. Created a Linux user account.
6. Added the user to the sudo group.
7. Switched to the newly created user account.
8. Checked the Ubuntu operating system information.
9. Checked the Linux kernel version.
10. Gathered CPU information using `lscpu`.
11. Checked available memory using `free`.
12. Checked disk usage using `df`.
13. Created the laboratory workspace and documentation files.
14. Organized the laboratory evidence and screenshots.
15. Prepared the project for GitHub.

## Linux Commands Used

| Command | Purpose |
|---|---|
| `whoami` | Displays the current username |
| `pwd` | Displays the current working directory |
| `hostname` | Displays the system hostname |
| `adduser` | Creates a new Linux user |
| `usermod` | Modifies a Linux user's settings |
| `groups` | Displays the groups assigned to a user |
| `su` | Switches to another user |
| `sudo` | Executes commands with administrative privileges |
| `cat /etc/os-release` | Displays Ubuntu operating system information |
| `uname -r` | Displays the Linux kernel version |
| `lscpu` | Displays CPU information |
| `free -h` | Displays memory information in a readable format |
| `df -h` | Displays disk space usage |
| `mkdir` | Creates directories |
| `touch` | Creates empty files |
| `ls` | Lists files and directories |
| `cd` | Changes the current directory |
| `nano` | Opens a terminal text editor |
| `git` | Manages version control and GitHub repositories |

## Skills Learned

Through this laboratory, I learned how to work with a Linux
command-line environment and perform basic system administration
tasks. I also learned how to create users, manage permissions,
collect system information, organize files, and document technical
activities using Markdown.

The activity also helped me understand how Git and GitHub can be
used to manage and submit project files. These skills provide a
foundation for future cloud computing and Linux-related activities.



# Laboratory 02 – Build the Cloud Infrastructure Blueprint

# Mission Overview

This laboratory focused on investigating a Linux cloud environment using KillerCoda. The activity covered compute, storage, networking, operating system resources, cloud providers, and basic cloud architecture.

# Objectives

* Investigate a Linux cloud server.
* Identify compute, storage, and networking resources.
* Understand cloud infrastructure components.
* Compare AWS, Azure, and Google Cloud.
* Create a simple cloud infrastructure diagram.
* Document the activities using Markdown and GitHub.

# Cloud Infrastructure Components

| Component        | Description                                 |
| ---------------- | ------------------------------------------- |
| Compute          | Provides processing power for applications. |
| Storage          | Stores files, data, and applications.       |
| Networking       | Allows systems and services to communicate. |
| Operating System | Manages the server and its resources.       |
| IAM              | Controls access to cloud resources.         |

## Tools Used

* KillerCoda
* Ubuntu Linux
* Visual Studio Code
* Git
* GitHub
* Markdown
* Draw.oi

## Linux Commands Executed

| Command               | Purpose                     |
| --------------------- | --------------------------- |
| `cat /etc/os-release` | Checks the operating system |
| `uname -r`            | Checks the kernel version   |
| `lscpu`               | Checks CPU information      |
| `nproc`               | Checks CPU cores            |
| `free -h`             | Checks RAM                  |
| `df -h`               | Checks disk usage           |
| `hostname`            | Checks hostname             |
| `hostname -I`         | Checks IP address           |

# Skills Learned

I learned how to investigate a Linux cloud server using terminal commands. I also learned how cloud infrastructure components work together and how to document my findings using Markdown, Git, and GitHub.

# Challenges Encountered

The main challenge was understanding the Linux system information and identifying the purpose of each cloud infrastructure component. I also learned how to organize screenshots and documentation in the GitHub repository.

# Cloud Architecture

The architecture includes:

```text
User
  ↓
Internet
  ↓
Cloud Network
  ↓
Compute Resource
  ↓
Storage Resource
```

The diagram is saved as:

`screenshots/cloud-architecture.png`

# Conclusion
This laboratory helped me understand the basic components of cloud infrastructure and how Linux can be used to investigate a cloud server. It also improved my skills in documentation, Git, and GitHub.

