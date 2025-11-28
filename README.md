# 🐧 Basic Linux Commands  
A beginner-friendly list of essential **Linux commands** used in Ethical Hacking, Pentesting, Bug Bounty, and CTFs (TryHackMe / HackTheBox).  
Includes **clear explanations + practical examples** for quick learning.

---

## 📁 File & Directory Basics

| Command | Explanation | Example |
|--------|-------------|---------|
| `ls -la` | List all files including hidden | `ls -la /home` |
| `cd /path` | Change directory | `cd /etc` |
| `pwd` | Show current directory | `pwd` |
| `mkdir folder` | Create directory | `mkdir reports` |
| `touch file.txt` | Create empty file | `touch notes.txt` |
| `rm file` / `rm -r folder` | Delete file/folder | `rm old.txt` |
| `mv old new` | Rename/move file | `mv test.txt backup.txt` |
| `cp a b` | Copy file | `cp report.txt copy-report.txt` |
| `cat file.txt` | View file content | `cat /etc/passwd` |
| `nano file.txt` | Edit file | `nano script.sh` |

---

## 🔐 Permissions & Ownership

| Command | Explanation | Example |
|--------|-------------|---------|
| `chmod 755 file` | Change permissions | `chmod 755 server.sh` |
| `chmod +x script.sh` | Make executable | `chmod +x exploit.sh` |
| `chown user:user file` | Change file owner | `sudo chown kali:kali abc.txt` |
| `sudo su` | Switch to root | `sudo su` |

---

## 🌐 Networking Commands

| Command | Explanation | Example |
|--------|-------------|---------|
| `ip a` | Show network interfaces | `ip a` |
| `ifconfig` | Old interface info | `ifconfig eth0` |
| `ping domain.com` | Test connectivity | `ping -c 4 google.com` |
| `curl URL` | Fetch webpage | `curl http://example.com` |
| `wget URL` | Download file | `wget https://example.com/file.zip` |
| `ss -tulnp` | Show listening ports | `ss -tulnp` |
| `nslookup domain` | DNS lookup | `nslookup google.com` |

---

## 🔍 Pentesting Essentials

| Command | Explanation | Example |
|--------|-------------|---------|
| `nmap -sV target` | Service/version scan | `nmap -sV 10.10.10.10` |
| `nmap -A target` | Aggressive scan | `nmap -A 192.168.1.5` |
| `nc -lvp 4444` | Start netcat listener | `nc -lvp 4444` |
| `nc target 4444` | Connect to listener | `nc 10.10.10.10 4444` |
| `grep "text" file` | Search inside file | `grep "password" config.txt` |
| `find / -name file` | Locate file in system | `find / -name id_rsa` |
| `strings binary` | Extract printable text | `strings exploit` |
| `tar -xf file.tar` | Extract tar archive | `tar -xf backup.tar` |
| `unzip file.zip` | Extract zip | `unzip secret.zip` |

---

## 🧪 System Information

| Command | Explanation |
|--------|-------------|
| `whoami` | Show current user |
| `uname -a` | Kernel + OS info |
| `hostname` | Show device name |
| `top` / `htop` | Process viewer |
| `df -h` | Disk usage |
| `free -m` | RAM usage |
| `ps aux` | List running processes |









**Example:**
```bash
ps aux | grep python


