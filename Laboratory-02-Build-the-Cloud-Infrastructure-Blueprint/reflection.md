# Mission Reflection

## 1. Which cloud infrastructure component do you think is the most important? Why?

For me, the most important cloud infrastructure component is **compute resources** because they provide the processing power needed to run applications, services, and other workloads. A cloud system needs processing power to perform tasks requested by users. Without compute resources, applications would not be able to run properly, even if the system has storage and network connectivity.

During this laboratory, I learned that compute resources can include the CPU and CPU cores available in a server. Using the KillerCoda environment, I was able to check the CPU information using the `lscpu` command and check the number of available processing units using `nproc`. These commands helped me understand that a cloud server still depends on computing resources just like a physical computer.

Compute is also important because the amount of processing power can affect the performance of applications. If an application receives many requests, it may require more computing resources to handle the workload. Cloud computing makes it possible for organizations to use computing resources without directly owning and maintaining physical servers.

However, compute cannot work alone. It needs storage to save data, networking to communicate with users and other services, and an operating system to manage the resources. This laboratory helped me understand that cloud infrastructure components are connected and work together.

Overall, I consider compute the most important component because it performs the actual processing required by applications and services. It serves as the main resource that allows workloads to run in a cloud environment.

## 2. How does Linux support cloud computing?

Linux supports cloud computing by providing a reliable operating system environment for servers and cloud workloads. It provides command-line tools that allow users and system administrators to inspect, configure, and manage server resources. In this laboratory, I used a Linux environment through KillerCoda, which gave me practical experience working with a cloud-based server.

One important advantage of Linux is that it allows users to manage a system through the terminal. Instead of depending only on a graphical interface, administrators can use commands to perform different tasks. For example, I used `cat /etc/os-release` to identify the operating system and `uname -r` to check the kernel version. I also used `lscpu` to investigate CPU information and `free -h` to check memory.

Linux also provides commands for investigating storage and networking. The `df -h` command can be used to check disk usage, while `hostname` and `hostname -I` can provide information about the server's hostname and IP address. These commands helped me understand how administrators can inspect a cloud server.

Another important feature is that Linux can support different applications and services running on servers. It provides an environment where cloud workloads can operate and where administrators can manage system resources.

This laboratory showed me that Linux is useful in cloud computing because it provides tools for system investigation and administration. Working with KillerCoda helped me become more comfortable with the Linux terminal and understand how a cloud-based Linux server can be managed.

Overall, Linux supports cloud computing by providing an operating system, command-line tools, and a flexible environment for running and managing cloud infrastructure.

## 3. Why is technical documentation important before deploying infrastructure?

Technical documentation is important before deploying infrastructure because it provides a clear record of the resources, configuration, design, and decisions related to a system. Before a cloud environment is deployed, engineers need to understand what resources are available and how those resources will work together. Proper documentation helps provide this information.

During this laboratory, I documented information about the Linux environment, including the operating system, kernel, CPU, memory, storage, hostname, and IP address. Recording this information made the investigation more organized and easier to understand. Instead of depending only on terminal output, the information could be saved in a Markdown report for future reference.

Documentation is also useful for troubleshooting. If a problem occurs after deployment, engineers can look at the documentation to understand the original configuration and identify possible causes. It can also help another engineer understand the system without having to repeat the entire investigation.

Another benefit is better planning. A cloud infrastructure may contain compute, storage, networking, and identity resources. Documentation can show how these components are connected and what each component is expected to do. This can help reduce mistakes during deployment.

In this laboratory, I also created a cloud infrastructure diagram. The diagram provided a simple visual representation of the user, Internet connection, cloud network, compute resource, and storage resource. A visual design can make the architecture easier to understand compared with text alone.

Technical documentation also improves communication between team members. Engineers, administrators, and other people involved in a project can use the same documentation as a reference.

Overall, technical documentation is important because it improves organization, planning, communication, troubleshooting, and maintenance. It helps engineers understand the infrastructure before deploying it and provides a useful reference for future changes.

## 4. What new skills did you learn during this laboratory activity?

During this laboratory activity, I learned several new skills related to Linux, cloud infrastructure, technical documentation, and GitHub. One of the main skills I developed was using Linux commands to investigate a cloud-based server. Before this activity, some of the terminal commands were unfamiliar to me, but using KillerCoda allowed me to practice them in an actual Linux environment.

I learned how to check operating system information using `cat /etc/os-release` and how to check the Linux kernel version using `uname -r`. I also learned how to investigate the CPU using `lscpu` and check the number of CPU cores using `nproc`. For memory and storage, I used `free -h` and `df -h`. I also learned how to check hostname and IP address information using `hostname`, `hostname -I`, and `ip -br addr`.

Another skill I learned was identifying the different components of cloud infrastructure. I learned that compute provides processing power, storage keeps data and files, networking allows communication, and the operating system manages the server environment. I also learned about identity and access management and its role in controlling access to cloud resources.

I improved my Markdown documentation skills during the activity. Instead of placing all information in one file, I organized the laboratory into separate documents such as the infrastructure report, cloud components, cloud provider comparison, and reflection.

I also practiced using Git and GitHub to manage my laboratory portfolio. I learned how to add changes, create commits, and push files to the repository using Visual Studio Code.

Overall, this laboratory gave me practical experience rather than only learning concepts from theory. The skills I developed can help me in future cloud computing activities, especially when working with Linux servers, documenting infrastructure, and managing projects through GitHub.

## 5. How has your GitHub portfolio improved after completing this mission?

My GitHub portfolio improved because it became more organized and complete after completing this laboratory mission. Instead of having only previous laboratory activities, I added a dedicated folder for Laboratory 02 that contains the required documentation and evidence. This makes it easier to organize my work and show my progress in Cloud Computing.

For Laboratory 02, I created separate Markdown files for different parts of the activity. These include `README.md`, `infrastructure-report.md`, `cloud-components.md`, `cloud-provider-comparison.md`, and `reflection.md`. Separating the information into different files makes the repository easier to navigate and understand.

I also added a `screenshots` folder for the evidence collected during the laboratory. The folder contains screenshots showing the server information, network information, storage information, and cloud architecture diagram. These files provide evidence that the activities were completed and help explain the information documented in the reports.

Another improvement is that I used Git to track my progress. I created meaningful commits after completing different parts of the laboratory and pushed the changes to GitHub. This allowed me to maintain a history of my work instead of simply uploading the files all at once.

The cloud architecture diagram also improved my portfolio because it provides a visual representation of a simple cloud infrastructure. It shows how a user can connect through the Internet to a cloud network, compute resource, and storage resource.

Overall, completing this mission made my GitHub portfolio more professional, organized, and useful as a record of my learning. It now contains both written documentation and visual evidence of my cloud infrastructure activities. The portfolio can also help me track the skills I have developed throughout the CCM101 course and serve as a reference for future laboratory activities.
