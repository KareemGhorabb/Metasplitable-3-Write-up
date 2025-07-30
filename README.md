# 🔐 Metasploitable 3 Pentesting Report

This repository contains a detailed penetration testing report targeting **Metasploitable 3**, a purposely vulnerable virtual machine used for ethical hacking and cybersecurity training. The report documents each phase of the attack lifecycle from reconnaissance to exploitation and post-exploitation.

📄 **Write-up:** [Metasploitable 3 Penetration Testing Report (PDF)](./Writeup.pdf)  
✍️ **Author:** Kareem Hossam Ghorab  
🏫 **Submitted to:** Digital Fortress & Orange Digital Center (ODC)  
🗓️ **Date:** 30/10/2024  
🎯 **Target IP:** `192.168.56.130`

---

## 🧪 Summary

This project showcases real-world penetration testing techniques conducted on **Metasploitable 3** using industry-standard tools and methodologies. Each discovered vulnerability was verified and exploited, and the process was documented with screenshots and analysis.

---

## 🔧 Tools Used

- **Netdiscover** – Network reconnaissance and IP detection  
- **Nmap** – Port scanning, service discovery, and version detection  
- **Metasploit Framework** – Vulnerability exploitation and payload delivery  
- **Wireshark** – Packet capture and network traffic analysis  
- **Kali Linux** – Main operating system used for the test environment  
- **VirtualBox / VMware** – Virtualization platform for lab setup

---

## 🔍 Attack Surface Explored

The following vulnerable services were identified and exploited:

1. **FTP – ProFTPD 1.3.5**
   - Anonymous login enabled
   - Exploited for remote shell access via Metasploit

2. **Apache – Port 80**
   - Explored web-based exploits
   - Achieved shell access through known vulnerabilities

3. **SSH – Port 22**
   - Tested for misconfigurations and weak authentication
   - Successfully accessed via exploited service

---

## 🧾 Report Highlights

- Detailed walkthrough of reconnaissance, enumeration, and exploitation  
- Screenshots of each key step and Metasploit sessions  
- Commands used during exploitation and system interaction  
- Clear recommendations to secure vulnerable services  
- Full exploitation of three major services (FTP, HTTP, SSH)

---

## 🏷️ Tags

`penetration-testing` `ethical-hacking` `metasploitable3` `nmap` `metasploit` `cybersecurity` `blue-team` `red-team` `writeup` `odc` `kali-linux`

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this content for **educational and non-commercial purposes**, provided appropriate credit is given.






---

## ⚠️ Disclaimer

This write-up and associated work were conducted in a **controlled lab environment** for **educational and ethical** purposes only.  
Do **not** attempt these techniques on any network or system you do not own or have explicit permission to test.

---

## 📬 Contact Me

Feel free to reach out for collaborations, questions, or feedback:

- 📧 **Email:** [Kareemhossam.weschool@gmail.com](mailto:Kareemhossam.weschool@gmail.com)  
- 💼 **LinkedIn:** [My Profile](https://www.linkedin.com/in/kareem-hossam-ghorab)  

