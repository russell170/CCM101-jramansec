# Automation Research Report

## 1. Bash Script

A Bash script is a text file containing Linux commands that can be executed together to automate tasks instead of typing each command manually. The `#!/bin/bash` line, called the shebang, tells the system to use the Bash interpreter to run the script.

## 2. Variables

Variables store values, such as folder paths or filenames, under a name that can be reused throughout a script. For example, using `$BACKUP_DIR` makes a script easier to update because I can change the backup folder path in one place instead of editing every command that uses it.

## 3. Cron Job

A cron job is a scheduled task in Linux that runs a command or script automatically at specified times or intervals. It is essential for cloud operations because it can automate repetitive tasks, such as backups and maintenance, without requiring someone to run them manually each time.