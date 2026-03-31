# 🎬 Open Source Audit — VLC Media Player

**Student Name:** Sridhar  
**Registration Number:** _(Add your reg. number here)_  
**Subject:** Open Source Software & Linux Scripting  

---

## 📌 About This Project

This project is a hands-on audit of an open-source software application done as part of my coursework. The goal was to explore how open-source software works in a real Linux environment — using shell scripting to inspect, analyze, and document the software from the ground up.

I chose **VLC Media Player** for this audit because it's one of the most widely used open-source tools in the world. It plays almost every audio and video format out there without needing extra codecs, and it perfectly represents what open-source is all about — the freedom to use, study, modify, and share software freely.

---

## 🛠️ Software Details

| Field       | Details                              |
|-------------|--------------------------------------|
| **Software**   | VLC Media Player                  |
| **License**    | GNU General Public License (GPL)  |
| **Developer**  | VideoLAN Organization             |
| **Type**       | Multimedia Player                 |

---

## ⚙️ Requirements

To run the scripts in this project, you'll need:

- A Linux environment (Ubuntu or WSL works fine)
- Bash shell
- VLC Media Player installed on your system

**To install VLC:**

```bash
sudo apt update
sudo apt install vlc
```

**Before running any script, give it execute permission:**

```bash
chmod +x *.sh
```

---

## 📂 Scripts Overview

This project includes 5 shell scripts, each focused on a different aspect of system and software auditing.

---

### 1. `script1_system_identity.sh` — System Identity Report

Displays basic system information — Linux distro, kernel version, current logged-in user, system uptime, and current date/time. Good starting point to understand the environment you're working in.

```bash
./script1_system_identity.sh
```

---

### 2. `script2_package_inspector.sh` — FOSS Package Inspector

Checks whether VLC is installed on the system and pulls its version info, package description, and a short note on open-source philosophy. Useful for understanding how Linux package management works.

```bash
./script2_package_inspector.sh vlc
```

---

### 3. `script3_disk_auditor.sh` — Disk and Permission Auditor

Scans important system directories and reports their permissions, ownership, and size. Also checks whether the VLC configuration folder exists on the machine.

```bash
./script3_disk_auditor.sh
```

---

### 4. `script4_log_analyzer.sh` — Log File Analyzer

Reads a specified log file, counts how many times a given keyword appears (e.g., "error"), and displays the most recent matching lines. Helpful for understanding how system logs work and how to parse them with bash.

```bash
./script4_log_analyzer.sh /var/log/syslog error
```

> **Note:** You may need `sudo` access depending on which log file you're reading.

---

### 5. `script5_manifesto_generator.sh` — Open Source Manifesto Generator

An interactive script that takes your name and some inputs, then generates a personalized open-source manifesto and saves it as a `.txt` file. A fun way to wrap up the project.

```bash
./script5_manifesto_generator.sh
```

---

## 📁 Project Structure

```
open-source-audit-vlc/
│
├── script1_system_identity.sh
├── script2_package_inspector.sh
├── script3_disk_auditor.sh
├── script4_log_analyzer.sh
├── script5_manifesto_generator.sh
└── README.md
```

---

## 💡 What I Learned

Working on this project gave me a much better understanding of how Linux systems are structured and how shell scripting can be used for real automation and auditing tasks. Going through VLC's license, dependencies, and configuration also helped me see the bigger picture of how open-source software is built and maintained by communities rather than corporations.

It also made me appreciate why open-source matters — not just as a technical concept, but as a philosophy around sharing knowledge and building things together.

---

## 👤 Author

**Sridhar**  
_(Add your college name, department, and year if you'd like)_

---

> *This project was done purely for educational purposes as part of an open-source software course.*
