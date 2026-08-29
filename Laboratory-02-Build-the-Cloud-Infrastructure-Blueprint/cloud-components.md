# Compute Resources
Purpose: Compute is the "brain" of any system — the CPU cycles and memory that actually execute code, run processes, and handle logic. Nothing else in the infrastructure matters if there's nothing to process requests.

Why it is importanant in cloud computing: In traditional (on-premise) IT, a company buys physical servers sized for peak demand, which sit idle most of the time. Cloud compute flips this: providers offer elastic compute (AWS EC2, Azure Virtual Machines, GCP Compute Engine) where you can spin up more CPU/RAM in minutes during high traffic and scale back down afterward, paying only for what's used. This elasticity is arguably the defining feature that makes cloud computing economically different from owning hardware.

Relate to KillerCoda: When you ran lscpu and free -h, you were essentially looking at the "instance size" of a mini virtual machine — the same kind of specs (vCPUs, RAM) that you'd choose when picking an EC2 instance type in AWS. The difference is scale: your KillerCoda sandbox has fixed, small specs, whereas real cloud compute lets you choose from dozens of instance sizes and even auto-scale.

# Storage Resources
Purpose: Storage holds data persistently — the OS files, application data, logs, and anything that needs to survive a reboot (unlike RAM, which is wiped).

Why it is important in cloud computing: Cloud storage is designed to be decoupled from compute — this is a key architectural principle. If a VM crashes or is replaced, the data on attached cloud storage (e.g., AWS EBS, S3) persists independently. Cloud storage also comes in different tiers (block storage for VMs, object storage for files/backups, archival storage for rarely accessed data), letting engineers optimize cost vs. speed vs. durability.

Relate to KillerCoda: Your df -h output shows the disk partitions mounted on your instance — this is analogous to an attached block storage volume on a real cloud VM. The mounted file systems represent how Linux organizes that storage (root /, /boot, /tmp, etc.), which is the same concept cloud engineers manage at scale when provisioning storage volumes for production servers.

# Networking Resources
Purpose: Networking is what makes a server reachable and lets it communicate with users, other servers, and the internet. Without networking, a powerful server with lots of storage is just an isolated box.

Why it is important in cloud computing: Cloud networking is more complex than a single IP address — it involves virtual private networks (VPCs), subnets, firewalls/security groups, load balancers, and DNS, all designed to control who can reach a resource and how traffic flows between services. This is critical for both security (isolating sensitive systems) and performance (distributing load across multiple servers).

Relate to KillerCoda: Running hostname and ip a reveals your instance's identity on the network — its hostname and assigned IP address. In a real cloud deployment, this single IP would sit inside a larger virtual network with routing rules and security groups controlling inbound/outbound traffic — KillerCoda simplifies this down to just the basic addressing layer.

# Operating System
Purpose: The OS is the layer between hardware and applications — it manages memory, schedules CPU processes, handles file systems, and provides the interface (shell, kernel) through which everything else operates.

Why it is importanant in cloud computing: Cloud providers let you choose your OS image when launching a VM (different Linux distros, Windows Server, etc.), and this choice affects compatibility, licensing cost, security patching responsibilities, and available tooling. Linux in particular dominates cloud infrastructure because it's open-source, lightweight, scriptable, and has strong native support for automation — which is why most cloud-native tools (Docker, Kubernetes, Terraform) are built with Linux in mind.

Relate to KillerCoda: cat /etc/os-release and uname -r show exactly which Linux distribution and kernel version your sandbox runs. This is the same "OS image" concept as choosing an AMI (Amazon Machine Image) in AWS or a VM image in Azure — the distro and kernel determine what software is available and how the system behaves.