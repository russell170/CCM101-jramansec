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
Compute Machine
  ↓
Storage Resource
  ↓
Security Group / Firewall
```

The diagram is saved as:

`screenshots/cloud-architecture.png`

# Conclusion
This laboratory helped me understand the basic components of cloud infrastructure and how Linux can be used to investigate a cloud server. It also improved my skills in documentation, Git, and GitHub.
