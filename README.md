# 🏠 Stivo's Homelab - Documentation Hub

Welcome to the central information dump of my homelab project.  
This repository exists so i can finally keep track of everything i build, break, fix, and break again.
**I live in a school dorm most of the week, so the server usually sits at home untouched. Whenever i finish messing with the hardware, i'll be able to work on it remotely.**
This repo helps me remember what i changed, what i planned, and lets me share my experience from this project.

---

## 📌 Why This Repo Exists
- To document **every important step** of the homelab journey.  
- To keep configs, setups, and ideas in one place.
- To avoid repeating fixes because i forgot how i solved something two weeks ago.  
- To give future me a good project to put on my resume.
- To share my experience as iam at it.

---

## 🧩 What's Inside
As the project grows, folders and files will appear as needed.

Expect:
- Hardware notes  
- Network configs  
- Proxmox stuff  
- Services and container setups  
- Automation attempts
- Security hardening  
- Backup plans
- Monitoring dashboards  
- Future ideas
- Etc...

---

## 💻 Current Hardware
*(Will update as the build changes)*

- **CPU:** Intel i5 8600.
- **RAM:** A calm luh 8GB DDR4. Will definetly upgrade this whenever possible.
- **Storage:** About 300GB of SSD storage and 1.3TB of HDD storage.
- **Network Equipment:** Currently no additional network equipment aside from the home router and some tplink deco wifi extenders. Will prolly add a raspberry pi to the structure later on as well. 
- **GPUs / Accelerators:** Nvidia Tesla K40 (will be used for lightweight LLMs), GeForce GTX 1050 (currently unused due to lack of an additional PCIex16 slot on the motherboard, will be used mainly for video processing and other lightweight services whenever implemented)

> Pictures might show up here eventually whenever the hardware issues are solved

---

## 📅 Current Plans
- **Reset BIOS password** - self explanatory
- **Install proxmox** - currently planning to install Proxmox VE 7.4 to match the older hardware im using on my server. The installation usb is ready, i just have to fix the issue just above this one to get started with software in the first place.

---

## 🛑 Current Problems
- **BIOS password refusing to die** - i assume it has to do with the NVRAM, bridging the JBAT1 pins and removing the lithium battery leaves the password alive, will work on this whenever i get home.

---

## ✅ Fixed past problems (unordered)
- **HDMI Issues** - fixed by removing the gpu from the PCIe slot and letting the integrated gpu in the cpu take priority + removing the i/o shield that blocked full passage for the hdmi cable (will put it back in the future)

---

## 🧠 Backstory
I started this homelab for a couple of interesting reasons:
1. I had to do something about my old computer not being used at all for 3 entire years.
2. I wanted to start getting into the practical side of hardware, networking, operating systems, security, and more. And a homelab perfectly covers all of these terms.
3. I wanted a new home environment from which i can enjoy all the advantages and cool things a homelab gives you and self host services, including LLMs.
4. It is simply a cool project to work on, during which you learn a lot from making thousands of mistakes and managing to fix them.
5. I want to have this on my resume in the future.

---

## 🗂️ How to Navigate
Each folder in this repo focuses on one part of the system.  
Even if you don't know the whole architecture, the structure is simple and readable.

---

## 🚀 Goals
- Build a clean, documented homelab environment
- Make it easily reproducible
- Learn the technical side of everything you get to do while building a homelab
- And mostly, **keep things stable and organized**

---

If you're reading this… hi
