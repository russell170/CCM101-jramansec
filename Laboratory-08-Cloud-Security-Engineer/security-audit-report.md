# Security Best Practices

### The Principle of Least Privilege (PoLP)

The Principle of Least Privilege means that each user or account should receive only the permissions needed to perform their assigned tasks. This is important in cloud computing because it reduces the risk of unauthorized access and limits the damage if an account is compromised.

### Attack Surface

The attack surface of a virtual machine is the total number of points where an attacker could try to get in, such as open network ports, running services, installed software, and user accounts. The more of these that are exposed, the more opportunities an attacker has, so reducing the attack surface makes the server harder to compromise.

### Default Deny Policy

A default deny policy blocks all traffic unless a rule explicitly allows it. This is safer than blocking specific hackers one by one because attackers can easily change their addresses and methods, and it is impossible to know every threat in advance, while allowing only the traffic that is needed keeps everything else closed.