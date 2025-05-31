# firewall-setup-task4

# Tool Used :

  UFW (for testing)

# Commands Used :
  all commands are listed in the "commands used in performing task-4.txt" file.

# Important note :
  You should see "Test-After-Block" image in that image the nmap scan shows port 23 show telnet

# Rules Added :
  Block Port 23 
  Allow Port 22

# Rules Deleted :
  Block Port 23




# Firewall Interview Questions and Answers

## 1. What is a firewall?
A firewall is a security device or software that monitors and filters incoming and outgoing network traffic based on predefined security rules. It acts as a barrier between a trusted internal network and untrusted external networks (like the internet).

---

## 2. Difference between stateful and stateless firewall?
- **Stateless Firewall**: Inspects each packet in isolation, without context of previous packets. It’s simpler but less secure because it doesn’t track active connections.
- **Stateful Firewall**: Maintains information about active connections (state table). It tracks the entire conversation, offering better security and dynamic decision-making.

---

## 3. What are inbound and outbound rules?
- **Inbound Rules**: Control incoming traffic to your system. They determine what external connections are allowed to enter.
- **Outbound Rules**: Control outgoing traffic from your system. They manage what data can leave your computer/network.

---

## 4. How does UFW simplify firewall management?
UFW (Uncomplicated Firewall) provides a simple command-line interface to manage firewall rules on Linux systems. It abstracts the complexity of `iptables` syntax, making it easier for beginners to set up firewall policies quickly.

---

## 5. Why block port 23 (Telnet)?
Port 23 is used by Telnet, a protocol that transmits data in plain text (unencrypted). This can expose sensitive data like passwords. Blocking port 23 helps prevent unauthorized access and enhances security.

---

## 6. What are common firewall mistakes?
- Allowing too much traffic (overly permissive rules).
- Forgetting to block unused ports.
- Not testing rules after configuring them.
- Ignoring updates or not maintaining firewall configurations.
- Misunderstanding the difference between inbound and outbound rules.

---

## 7. How does a firewall improve network security?
A firewall enforces security policies by allowing only trusted and necessary traffic, while blocking malicious or suspicious connections. It helps prevent unauthorized access, data breaches, and certain types of attacks.

---

## 8. What is NAT in firewalls?
NAT (Network Address Translation) is a technique used by firewalls to map internal private IP addresses to a public IP address (and vice versa). This enhances security by hiding internal IP structures from the external network and allows multiple devices to share a single public IP address.

---

