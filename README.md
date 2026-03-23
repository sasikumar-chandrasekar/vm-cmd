# 🐧 Linux / VM Basic Commands Cheat Sheet

---

## 📂 Directory Navigation Commands

| Command | Meaning |
|--------|--------|
| `pwd` | Show current working directory |
| `ls` | List files and directories |
| `ls -l` | List files with detailed information |
| `ls -a` | List all files including hidden files |
| `cd /home` | Change directory to /home |
| `cd ..` | Go back one directory level |
| `cd ~` | Go to home directory |

---

## 📁 File & Directory Management

| Command | Meaning |
|--------|--------|
| `mkdir test` | Create a directory |
| `mkdir -p parent/child` | Create nested directories |
| `touch file.txt` | Create an empty file |
| `cat file.txt` | Display file content |
| `less file.txt` | View file content page by page |
| `cp file.txt backup.txt` | Copy a file |
| `cp -r test test_backup` | Copy directory recursively |
| `mv file.txt data.txt` | Move or rename file |
| `rm data.txt` | Delete a file |
| `rm -r test` | Delete directory and contents |

---

## 💻 System Information Commands

| Command | Meaning |
|--------|--------|
| `uname -a` | Show kernel, OS, architecture |
| `hostname` | Display system hostname |
| `uptime` | Show system uptime & load |
| `lscpu` | Show CPU details |
| `cat /etc/os-release` | Show OS version details |

---

## 💾 Disk & Memory Commands

| Command | Meaning |
|--------|--------|
| `df -h` | Show disk usage (human readable) |
| `du -sh /var/log` | Show directory size |
| `free -h` | Show RAM usage |
| `mount` | Show mounted file systems |

---

## ⚙️ Process Management

| Command | Meaning |
|--------|--------|
| `top` | Real-time running processes |
| `ps -ef` | Show all running processes |
| `ps -ef \| grep nginx` | Search process by name |
| `kill 1234` | Kill process by PID |
| `kill -9 1234` | Force kill process |

---

## 🌐 Network Commands

| Command | Meaning |
|--------|--------|
| `ip a` | Show IP & network interfaces |
| `ip route` | Show routing table |
| `ping google.com` | Test connectivity |
| `ss -tuln` | Show open ports |
| `nslookup google.com` | Check DNS resolution |

---

## 👤 User & Permission Management

| Command | Meaning |
|--------|--------|
| `whoami` | Show current user |
| `who` | Show logged-in users |
| `chmod 755 script.sh` | Change file permissions |
| `chmod u+rwx file.txt` | Give full permission to owner |
| `chown user:user file.txt` | Change file ownership |

---

## 📦 Package Management (Ubuntu / Debian)

| Command | Meaning |
|--------|--------|
| `sudo apt update` | Update package list |
| `sudo apt install nginx` | Install package |
| `sudo apt remove nginx` | Remove package |

---

## 📦 Package Management (RHEL / CentOS)

| Command | Meaning |
|--------|--------|
| `sudo yum install nginx` | Install package |

---

## 🔄 Service Management (systemd)

| Command | Meaning |
|--------|--------|
| `sudo systemctl start nginx` | Start service |
| `sudo systemctl stop nginx` | Stop service |
| `sudo systemctl restart nginx` | Restart service |
| `sudo systemctl enable nginx` | Enable at boot |
| `sudo systemctl status nginx` | Check service status |

---

## 🔌 VM Power Commands

| Command | Meaning |
|--------|--------|
| `sudo reboot` | Reboot VM |
| `sudo shutdown now` | Shutdown immediately |
| `sudo shutdown +5` | Shutdown after 5 minutes |

---

## 🛠️ Help & Troubleshooting

| Command | Meaning |
|--------|--------|
| `man ls` | Show manual page |
| `ls --help` | Show help |
| `which ls` | Show command path |
| `history` | Show command history |
| `clear` | Clear terminal |

---
