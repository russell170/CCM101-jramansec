## Checkpoint 7 – Linux Server Investigation

For this checkpoint, I launched a Linux server using the KillerCoda Playground. I used Linux commands to identify the operating system, CPU information, memory, and available disk space.

### Linux System Information

| Information | Command Used | Result |
|---|---|---|
| Operating System | `cat /etc/os-release` | Ubuntu 24.04.4 LTS (Noble Numbat) |
| CPU Information | `lscpu` | Intel Xeon E312xx (Sandy Bridge), 1 CPU, 1 core, 1 thread per core, x86_64 architecture, virtualized under KVM |
| Memory | `free -h` | Total: 1.9Gi, Used: 408Mi, Free: 871Mi, Available: 1.5Gi |
| Disk Space | `df -h` | Root (`/dev/vda1`): 19G total, 5.4G used, 13G available (30% used) |

### Cloud Migration Options

If this Linux server were migrated to the cloud, it could be hosted using virtual machine services from the major cloud providers.

* **AWS:** Amazon EC2
* **Microsoft Azure:** Azure Virtual Machines
* **Google Cloud:** Compute Engine

These services provide virtual machines that can run Linux-based workloads in the cloud. The Linux server's CPU, memory, storage, and operating system requirements would need to be considered when selecting the appropriate cloud instance or virtual machine configuration. Based on this server's specs (1 vCPU, ~2GB RAM, ~19GB disk), it would correspond to a small/burstable instance tier such as an AWS **t3.micro** (EC2), Azure **B1s** (Burstable series), or GCP **e2-small** (Compute Engine) — all of which are designed for low-resource, cost-efficient workloads similar to this sandbox environment.

### Screenshot Evidence

![KillerCoda Linux Terminal](screenshots/killercoda-terminal.png)

The screenshot shows the Linux commands used to identify the server's operating system, CPU, memory, and disk space.