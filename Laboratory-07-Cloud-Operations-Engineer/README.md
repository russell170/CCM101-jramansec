# Laboratory 07 – The Cloud Operations Engineer

## Mission Overview

This laboratory activity introduced observability and monitoring from the perspective of a Cloud Operations Engineer (Site Reliability Engineer) at CloudNova Technologies. The goal was to run a baseline health check on a Linux host, deploy a client's Nginx web server in a container, generate test traffic, and use logs and real-time metrics to show that the infrastructure is healthy and ready for a surge in users.

## Objectives

* Use native Linux command-line tools to monitor host CPU, memory, and disk capacity.
* Deploy a web container and track its real-time performance using Docker metrics.
* Generate web traffic and extract application access logs for analysis.
* Translate raw performance data into a readable technical report using Markdown.
* Continue expanding a professional GitHub Cloud Computing Portfolio.

## Monitoring Commands Executed

| Command | Purpose |
|---|---|
| `free -h` | Checked the host's total, used, and available memory (RAM) |
| `df -h` | Checked the host's disk capacity and available storage |
| `top` | Viewed running processes and live CPU load on the host |
| `docker run -d -p 8080:80 --name client-website nginx` | Deployed the Nginx web server in the background on port 8080 |
| `docker ps` | Confirmed the `client-website` container was running |
| `curl http://localhost:8080` | Simulated a user visiting the website (run three times) |
| `curl http://localhost:8080/hidden-admin-page` | Simulated a request for a missing page to generate a 404 error |
| `docker logs client-website` | Retrieved the container's application logs to find the 200 and 404 requests |
| `docker stats` | Viewed the container's live CPU, memory, and network usage |

## Skills Learned

I learned how to establish a baseline for a Linux host by checking memory, disk space, and CPU load with `free -h`, `df -h`, and `top`. I also learned how to generate test traffic against a containerized web server using `curl`, including a request that intentionally triggers a 404 error. Reading the container's logs with `docker logs` showed me how a Cloud Operations Engineer finds specific errors, while `docker stats` showed me how to check that a container is using very little CPU and memory. Overall, this activity helped me understand how logs and metrics work together to prove that an application is healthy.