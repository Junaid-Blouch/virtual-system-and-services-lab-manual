# Virtual System and Services Lab Manual

**University:** Muhammad Nawaz Sharif University of Engineering and Technology, Multan  
**Program:** BS‑IT | **Semester:** 6th | **Session:** 2023–2027  
**Student:** M. Junaid (Reg. No. 2023‑IT‑39)  
**Supervised by:** Mam Ayesha Alam  

---

## 📚 Overview

This repository contains a complete lab manual for the **Virtual System and Services** course.  
It covers:

- Virtualization fundamentals – what is a VM, hypervisor types (Type 1 / Type 2)
- Installing Oracle VirtualBox and obtaining OS images (Kali, Ubuntu, Linux Mint)
- Creating and configuring VMs (CPU, RAM, storage, display settings)
- Guest OS installation (Linux Mint / Ubuntu) with troubleshooting
- Resource monitoring: `du`, `df`, `free`, `top`, `htop`, `vmstat`, `iostat`
- Stress testing the VM (CPU, RAM) using `stress` and `stress-ng`
- Snapshots – saving, modifying, and restoring VM state
- Networking modes: **NAT** (safe internet) vs **Bridged** (full network member)
- Running multiple VMs simultaneously – observing CPU, RAM, disk usage
- Peripheral virtualization – shared clipboard, drag & drop, shared folders
- VM cloning and export/import (OVA files)
- Suspend / resume vs shutdown
- Local VM vs Cloud VM comparison (AWS, Azure, GCP)
- Linux commands in local vs cloud environments (`ssh`, `scp`, `systemctl`, `df -h`, `htop`)

All tasks include objectives, step‑by‑step procedures, command examples, screenshots, and Q&A.

---

## 📁 Lab Tasks Index

| Task # | Topic |
|--------|-------|
| 01 | Fundamentals of virtual systems – what is a VM, how it works, benefits |
| 02 | Virtualization types & host compatibility check (Intel VT‑x / AMD‑V) |
| 03 | Installing VirtualBox and obtaining OS images (Kali, Ubuntu) |
| 04 | VM creation, CPU virtualization, bootable Ubuntu USB |
| 05 | Guest OS installation (Linux Mint) – step‑by‑step + troubleshooting |
| 06 | Managing virtual hard disk resources – `du`, `lsblk`, `df`, `free`, `top`, `htop` |
| 07 | Checking resource allocation & stress testing (`stress`, `stress-ng`) |
| 08 | Snapshots – creation, modification, restoration |
| 09 | NAT networking – safe internet for VM |
| 10 | Bridged networking – VM as full network member |
| 11 | Running two VMs simultaneously – resource distribution (Task Manager analysis) |
| 12 | Peripheral virtualization – shared clipboard, drag & drop, shared folders |
| 13 | VM cloning and export/import (OVA) – differences explained |
| 14 | Suspend, resume and VM state management vs shutdown |
| 15 | Comparison table: Local VM vs Cloud VM (AWS/Azure/GCP) |
| 16 | Linux commands in local vs cloud VM – `ssh`, `scp`, `systemctl`, `df -h`, `htop` |

---

## 🛠️ Requirements & Tech Stack

- **Oracle VirtualBox** (v7.x or later) – free download from [virtualbox.org](https://www.virtualbox.org)
- **A PC with hardware virtualization support** (Intel VT‑x / AMD‑V) – enable in BIOS
- **OS images** (ISOs):
  - Linux Mint (Cinnamon edition recommended)
  - Ubuntu Desktop
  - Kali Linux (optional)
- **Host OS:** Windows / Linux / macOS (with at least 8 GB RAM, 50 GB free disk)

All tools used inside the VMs (Linux commands) are built‑in or installable via `apt`.

---

## 📖 How to Use This Manual

### 1️⃣ View Online (No Download)
- Click on the PDF file in this repository (e.g., `Virtual-System-Services-Lab-Manual.pdf`).
- GitHub will render a preview – read it directly in your browser.

### 2️⃣ Download the PDF
- Click the PDF → **Download** button (or right‑click **Raw** → Save link as).
- Open with any PDF reader (Adobe Acrobat, Chrome, Foxit, etc.).

### 3️⃣ Clone the Repo for Offline Access
```bash
git clone https://github.com/Junaid-Blouch/virtual-system-and-services-lab-manual.git
