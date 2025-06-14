# Ethical Hacking via Armitage

**🛠️ Exploitation Lab: Windows 10 Attacks, Client-Server Interception, and Post-Exploitation Control**

**Author:** Mark Ford Jr.

---

## 🎯 Overview

This ethical hacking project demonstrates end-to-end penetration testing on Windows 10 virtual environments using **Armitage**, **Metasploit**, and **Kali Linux**.
It includes client-server interruption, privilege escalation, **multi-user testing**, **camera hijacking**, and **keylogger installation** — all within a legally controlled lab.

---

## 🔐 Objectives

* Exploit vulnerable Windows 10 and legacy systems in isolated VMs
* Simulate client-server attacks across two user profiles
* Perform real-world post-exploitation: webcam access, persistent keylogger
* Log, document, and replay exploitation steps for training purposes

---

## 🧰 Tools & Technologies

* **Kali Linux** – Penetration testing OS
* **Armitage** – GUI interface for Metasploit
* **Metasploit Framework** – Exploitation engine
* **VirtualBox** – VM hosting (Windows 10, XP, 7)
* **Sysinternals** – For behavior monitoring and testing
* **Custom Python Keylogger** – Installed during post-exploitation
* **Webcam Capture Payloads** – For hijacking camera feed

---

## 💻 Exploits & Techniques Used

| Technique                   | Target OS     | Outcome                             |
| --------------------------- | ------------- | ----------------------------------- |
| MS08-067                    | Windows XP    | Remote code execution               |
| EternalBlue (MS17-010)      | Windows 7     | SYSTEM-level shell                  |
| Web Delivery Payload (HTTP) | Windows 10    | Command execution with user access  |
| Meterpreter Webcam Snap     | Windows 10    | Captured images from camera         |
| Persistent Keylogger Deploy | Windows 10    | Logged keystrokes from both users   |
| Session Hijack (multi-user) | Client/Server | Intercepted and manipulated traffic |

---

## 🧪 Test Lab Setup

* **2 Windows 10 user profiles** configured for real-world client-server simulation
* **Kali host** on bridged network mode
* VMs fully isolated with no external access
* Manual logs maintained for each action

---

## 🔍 Post-Exploitation Actions

* **Keylogger** installation (custom Python-based, persistent on reboot)
* **Webcam control** using `meterpreter > webcam_snap`
* **User enumeration** and privilege escalation
* Simulated **session hijack** with credential reuse across services
* Captured keystrokes: login attempts, emails, and browser entries

---

## 📊 Results

* Demonstrated **full exploitation chain** on Windows 10 systems
* Successfully hijacked two user sessions and exfiltrated sensitive data
* Gained persistent access with **no AV detection in lab**
* Clear documentation for future student or SOC analyst reference

---

## ⚠️ Legal Notice

All activities were performed in a **legal and isolated virtual lab**.
Unauthorized access or use of these techniques on real systems is illegal.
This project is for **educational and training purposes only**.

---

## 🧭 Future Enhancements

* Add privilege escalation for Linux targets
* Test AV evasion techniques and defender bypass
* Integrate logging into centralized SIEM
* Expand to social engineering payloads (e.g., malicious PDFs, links)

---

## 📞 Contact

**Mark Ford Jr.**
GitHub: [markfordjr](https://github.com/markfordjr)

Project Repo: [Ethical Hacking via Armitage](https://github.com/markfordjr/Ethical-Hacking-via-Armitage)

---

## 📄 License

MIT License
