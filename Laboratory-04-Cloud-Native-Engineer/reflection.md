# Mission Reflection

## My Reflection

Docker is much faster to set up compared to installing a complete operating system on a virtual machine. A virtual machine needs to boot an entire operating system, which requires more time, memory, and storage. Docker containers are lightweight because they share the host operating system, allowing applications such as Nginx to start within seconds.

The port mapping `-p 8080:80` is necessary because it connects port 8080 of the host machine to port 80 inside the Nginx container. Nginx normally listens on port 80 inside the container. By mapping it to port 8080, I can access the Nginx web server through `http://localhost:8080` from the host environment.

When `docker rm` is used, the container itself is completely removed. Any data stored only inside the container and not saved using a volume or another persistent storage method can be lost. This shows the importance of using persistent storage when an application needs to keep data after a container is removed.

Containerization can improve DevOps collaboration because developers can package applications together with their required dependencies. This helps reduce differences between development, testing, and production environments. Teams can also use the same container image, making application deployment more consistent and easier to manage.

My GitHub portfolio is evolving from documenting basic cloud concepts to showing practical cloud-native skills. In previous laboratories, I worked with cloud infrastructure, multiple cloud platforms, and service comparisons. In this laboratory, I added Docker commands, container deployment, Nginx testing, and container lifecycle management. These activities make my portfolio a record of both my theoretical knowledge and hands-on experience with cloud technologies.