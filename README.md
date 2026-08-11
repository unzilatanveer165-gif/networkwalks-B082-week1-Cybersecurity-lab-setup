# networkwalks-B082-week1-Cybersecurity-lab-setup
Cybersecurity Lab setup
Project Overview
This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.

The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

🎯 Objectives
The main objectives of this project are to:

Install and configure VirtualBox.
Install/import Kali Linux as a virtual machine.
Create a private NAT Network for the cybersecurity lab.
Configure network connectivity for Kali Linux.
Assign a consistent IP address to the Kali VM.
Verify network connectivity and DNS resolution.
Take a clean VM snapshot for recovery.
Document the complete setup process.
Prepare the environment for future cybersecurity projects.
🛡️ Purpose of the Lab
The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

Network reconnaissance
Port scanning
Vulnerability assessment
Packet analysis
Web security testing
Exploitation practice
Security-tool experimentation
⚠️ Important: This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.

Lab Setup Procedure
Step 1. Download & install 7-zip: https://7-zip.org/download.html
Step 2. Download & install Virtualbox on your laptop/PC: https://virtualbox.org/wiki/Downloads
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1cadcdd1-4b10-4ebf-8e72-4348ed1d20c6" />

Step 3. Configure the network settings on your Virtualbox (create NATNetwork in 10.0.0.0/24)
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/28a51483-76b7-4a0b-824a-195d5d8b08e9" />

Step 4. Download & import Kali Linux Virtual Machine in your Virtualbox: https://kali.org/get-kali
<img width="1218" height="677" alt="image" src="https://github.com/user-attachments/assets/328e998f-fd15-4dbd-878f-bd107e9c1ee7" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2ebd81d5-5db0-4e05-9852-5b7616146caa" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f3646487-c39d-4268-862c-3543a432a517" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/79b070e1-8a04-4141-a8db-69d2ec2370da" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9217eef8-6b35-4477-af06-10b93aeabca9" />

Step 5. Setup the IP configuration of Kali Linux

Step 6. Take snapshot of the VM
