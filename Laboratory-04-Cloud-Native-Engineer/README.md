# Laboratory 04 – The Cloud-Native Engineer

## Mission Overview
This laboratory focused on understanding the difference between traditional virtual machines and containers. I used Docker in a KillerCoda Ubuntu environment to pull and deploy an Nginx container. I also practiced basic Docker container lifecycle operations such as checking, stopping, and removing a container.

## Objectives
- Differentiate between traditional Virtual Machines (VMs) and Containers.
- Access a Docker-enabled cloud environment using KillerCoda.
- Execute fundamental Docker CLI (Command Line Interface) commands.
- Pull, run, manage, and terminate a containerized application (Nginx).
- Create professional technical documentation of container operations using Markdown.
- Continue developing a well-organized GitHub Cloud Computing Portfolio.

## Docker Commands Executed

| Command | Purpose |
|---|---|
| `docker --version` | Verified Docker was installed |
| `docker info` | Checked the current status of the Docker environment |
| `docker pull nginx` | Downloaded the official Nginx image from Docker Hub |
| `docker run -d -p 8080:80 --name nginx-server nginx` | Ran the Nginx container in detached mode, mapping host port 8080 to container port 80 |
| `curl http://localhost:8080` | Verified the web server was responding with the Nginx welcome page |
| `docker ps` | Listed currently running containers |
| `docker stop nginx-server` | Stopped the running Nginx container |
| `docker ps -a` | Verified the container had stopped |
| `docker rm nginx-server` | Removed the stopped container completely |

## Skills Learned
I learned how to use basic Docker commands to manage containers. I learned how to pull an image, create and run a container, map ports, verify a web server, stop a container, and remove it. I also improved my understanding of how containers provide a lightweight alternative to traditional virtual machines.

## Challenges Encountered
One challenge was understanding the purpose of port mapping when running the Nginx container. I learned that port 8080 on the host must be mapped to port 80 inside the container so that the Nginx web server can be accessed. Another challenge was understanding the difference between stopping and removing a container. Through the activity, I learned that stopping a container does not remove it, while docker rm removes the container completely.