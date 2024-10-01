# Ethical-Hacking-via-Armitage

Project Description:
This GitHub project details my experience as a student participating in a cybersecurity field trip, where I engaged in the three phases of penetration testing using a tool called Armitage. The project took place in a lab environment set up to mimic real-world cybersecurity scenarios.

Lab Setup:
Our lab consisted of two virtual machines (VMs): one running Kali Linux as the attacker and another running Windows 10 as the target, managed through Oracle VM VirtualBox on a host computer with Kubuntu Linux. From the Kali VM, I utilized Armitage to explore and exploit vulnerabilities in a chat server application (vchat.exe) running on the Windows VM.

Steps to Set Up the Lab:
Initially, I launched Oracle VM VirtualBox Manager on the host computer to start both the Kali and Windows VMs. After logging into Kali with the designated credentials, I accessed the Windows VM to activate the chat server. To facilitate the penetration test, I disabled the real-time protection on Windows to prevent any interference with our testing procedures.

Penetration Testing Phases:
The testing began with reconnaissance, where I employed Armitage to scan for and analyze network services on the Windows VM. This phase involved identifying the VM’s IP address and using targeted scans to ascertain active services and vulnerabilities. During the exploitation phase, I focused on exploiting a known vulnerability within vchat.exe. This required several attempts to successfully breach the system, using Armitage’s array of attack tools. Once access was gained, in the post-exploitation phase, I navigated the compromised system through a Meterpreter shell, executing commands to view and manipulate files, deepening my understanding of the attacker’s capabilities in a real intrusion scenario.

Educational Objectives:
Through this field trip, I significantly enhanced my practical cybersecurity skills, particularly in setting up and maneuvering through virtual environments tailored for security testing. I gained firsthand experience in conducting penetration tests from initial scanning to final exploitation and post-exploitation analysis. This project not only reinforced my theoretical knowledge of network vulnerabilities and attack mechanisms but also provided practical insights into the dynamics of cybersecurity defenses and ethical hacking.
