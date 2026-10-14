# Laboratory 09 – The Cloud Automation Engineer

## Mission Overview

This laboratory activity focuses on automating application backups using Bash scripting and Linux Cron. The task involves creating sample application data, writing a script to compress the data into a backup archive, assigning executable permission, and scheduling the script to run automatically every night at 2:00 AM.

## Objectives

* Understand the fundamental syntax of a Bash shell script, including variables and basic commands.
* Use a command-line text editor (nano) to write and save executable scripts.
* Modify Linux file permissions using the `chmod` command.
* Understand task scheduling and the syntax of a Linux crontab.
* Document automation code and Cron job configurations using Markdown.
* Complete the final chapter of the GitHub Cloud Computing Portfolio.

## Commands Executed

| Command | Purpose |
|---|---|
| `mkdir app-data` | Created a dummy folder to represent the client's data |
| `echo "This is critical client data." > app-data/data.txt` | Created a test file inside the data folder |
| `nano backup.sh` | Created and edited the backup script |
| `./backup.sh` | Ran the script (it failed with "Permission denied" the first time) |
| `chmod +x backup.sh` | Gave the script execute permission |
| `ls -l backups/` | Verified that the compressed `.tar.gz` backup file was created |
| `crontab -l` | Listed the scheduled cron jobs |
| `env EDITOR=nano crontab -e` | Opened the cron table in nano to add the schedule |

## Skills Learned

I learned how to write a Bash script with variables, create a backup with `tar`, and use a timestamp so each backup has a unique name. I also learned why Linux requires execute permission before a script can run and how `chmod +x` grants it. Scheduling the script with the cron expression `0 2 * * *` showed me how a task can run automatically every night without anyone pressing a button, which is the core idea of automation in cloud operations.