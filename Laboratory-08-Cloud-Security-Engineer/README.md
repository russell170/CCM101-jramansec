# Laboratory 08 – The Cloud Security Engineer

## Mission Overview

This laboratory activity applied cloud security concepts from the point of view of a Cloud Security Engineer at CloudNova Technologies. A web server had been deployed without any network security, so the task was to deploy a web application, then lock the server down with the Uncomplicated Firewall (UFW) using a Default Deny policy while allowing only the services the client needs: SSH for administration and port 8080 for the web application.

## Objectives

* Understand the concept of the Attack Surface and the Principle of Least Privilege (PoLP).
* Perform a basic security audit of active network ports on a Linux server.
* Configure the Uncomplicated Firewall (UFW) with a Default Deny policy.
* Implement granular port management to selectively allow SSH and HTTP traffic.
* Document firewall rules and security best practices using Markdown.
* Continue expanding a professional GitHub Cloud Computing Portfolio.

## Commands Executed

| Command | Purpose |
|---|---|
| `docker run -d -p 8080:80 --name secure-web-app nginx` | Deployed the Nginx web application on port 8080 |
| `docker ps` | Confirmed the `secure-web-app` container was running |
| `curl http://localhost:8080` | Simulated a user request to verify the application was reachable |
| `sudo ufw allow ssh` | Allowed SSH (port 22) so administrators are not locked out |
| `sudo ufw default deny incoming` | Blocked all incoming traffic by default |
| `sudo ufw default allow outgoing` | Allowed all outgoing traffic |
| `sudo ufw enable` | Activated the firewall |
| `sudo ufw status verbose` | Checked that the firewall was active with the Default Deny policy |
| `sudo ufw allow 8080/tcp` | Allowed TCP traffic on port 8080 for the web application |
| `sudo ufw status numbered` | Verified that the new rule was added to the firewall list |

## Skills Learned

Through this activity, I practiced deploying an Nginx container, testing a web application, configuring UFW firewall rules, and verifying network access. I also learned why SSH access should be allowed before enabling a firewall and how a default-deny policy helps reduce a server's attack surface.