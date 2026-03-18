# 🌐 Day 02 – Networking Fundamentals

## 📚 What I Learned

Today I learned the basics of networking, which is a very important concept in DevOps and cloud computing.

- What is networking
- How systems communicate with each other
- Basics of IP addresses
- Difference between Public and Private IP
- Introduction to ports and protocols

---

## 🌍 Key Concepts

### 🔹 IP Address
An IP address is a unique identifier assigned to a device on a network.

- Example: `192.168.1.1` (Private IP)
- Example: `54.75.109.215` (Public IP)

---

### 🔹 Public vs Private IP

| Type | Description |
|------|------------|
| Public IP | Used to access systems over the internet |
| Private IP | Used inside a local network |

---

### 🔹 Ports

Ports help identify specific services running on a system.

- Port 80 → HTTP (Web)
- Port 443 → HTTPS (Secure Web)
- Port 22 → SSH (Remote access)

---

### 🔹 Protocols

Protocols define how data is transmitted.

- HTTP / HTTPS → Web communication
- TCP → Reliable communication
- UDP → Faster but less reliable

---

## ⚙️ Hands-on Practice

- Launched an EC2 instance
- Connected to server using SSH
- Installed Nginx
- Understood how public IP connects browser to server
- Learned about opening port 80 in Security Group

---

## 🚀 Key Takeaway

Networking is the backbone of DevOps.  
Without understanding networking, deploying and managing applications in the cloud is not possible.

---

## 📌 Commands Used

```bash
sudo apt update
sudo apt install nginx
sudo systemctl start nginx
sudo systemctl status nginx
