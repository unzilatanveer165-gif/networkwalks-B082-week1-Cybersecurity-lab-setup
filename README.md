# networkwalks-B082-week1-Cybersecurity-lab-setup
🔐 Cybersecurity Lab Environment Setup

Building an isolated virtual lab for penetration testing and ethical hacking practice

📌Project Overview: This project focuses on setting up a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.

📌The purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be performed safely and repeatedly.

The lab is configured on a private virtual network so that additional machines can be added later and used as targets for authorized security testing.

🎯 Objectives:

The main objectives of this project are to:

1.Install and configure VirtualBox.
2.Install/import Kali Linux as a virtual machine.
3.Create a private NAT Network for the cybersecurity lab.
4.Configure network connectivity for Kali Linux.
5.Assign a consistent IP address to the Kali VM.
6.Verify network connectivity and DNS resolution.
7.Take a clean VM snapshot for recovery.
8.Document the complete setup process.
9.Prepare the environment for future cybersecurity projects.

🛡️ Purpose of the Lab:

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

Lab Setup Procedure:

Step 1. Download & install 7-zip: https://7-zip.org/download.html

Step 2. Download & install Virtualbox on your laptop/PC: https://virtualbox.org/wiki/Downloads

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1cadcdd1-4b10-4ebf-8e72-4348ed1d20c6" />


Step 3. Configure the network settings on your Virtualbox (create NATNetwork in 10.0.0.0/24)

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/28a51483-76b7-4a0b-824a-195d5d8b08e9" />


Step 4. Download & import Kali Linux Virtual Machine in your Virtualbox: https://kali.org/get-kali

<img width="1218" height="677" alt="image" src="https://github.com/user-attachments/assets/328e998f-fd15-4dbd-878f-bd107e9c1ee7" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/405bc864-b593-436d-ae38-b1ee27602fac" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/2ebd81d5-5db0-4e05-9852-5b7616146caa" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/75036c6a-4513-42b9-8e56-62d38c6a74e0" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f3646487-c39d-4268-862c-3543a432a517" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9217eef8-6b35-4477-af06-10b93aeabca9" />


Step 5. Setup the IP configuration of Kali Linux

<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/611ed5f6-8b44-461d-8d4d-e0623f4494ef" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/02232628-f641-471b-9f15-15e35f8db831" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/83b0be28-8a76-437d-91d2-27d1f7135a36" />
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/7b02ef1a-fc3e-4ffb-b198-71f422c3168c" />
UPDATED:
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/b5962ef5-5abd-41dd-a093-42d217dc7af0" />
<img width="1599" height="720" alt="image" src="https://github.com/user-attachments/assets/b0956521-015c-4180-8116-5069b93ec25a" />


Step 6. Take snapshot of the VM

<img width="1358" height="710" alt="image" src="https://github.com/user-attachments/assets/c8863191-d3af-4433-a28d-a2160849a171" />


Problem I faced: Internet Connectivity After Static IP Configuration

After manually configuring the IPv4 settings, Internet connectivity may fail depending on the Kali/NetworkManager configuration.

One workaround used during this lab was:

sudo nmcli connection modify "Wired connection 1" ipv4.dad-timeout 0
The network connection was then restarted/rebooted and connectivity was tested again.
<img width="1600" height="1200" alt="image" src="https://github.com/user-attachments/assets/a38c2894-adad-4fef-b10f-f3273aa49675" />



What I Learned

Through this project, I learned how to create and configure a virtual environment for cybersecurity practice.

The most important concepts I learned include:

1. NAT vs NAT Network
   A standard NAT configuration and a NAT Network serve different purposes.

  "A NAT Network allows multiple VMs connected to the same virtual network to communicate with one another while providing network          address translation for external connectivity."

  This makes it useful for building a multi-machine cybersecurity laboratory.

2. Virtual Machine Networking
   
  I learned how VirtualBox virtual network adapters connect virtual machines to different types of networks and how network configuration   affects communication between machines.

3. Static IP Configuration
   
  I learned how to configure and verify IPv4 addressing, subnet masks, gateways, and DNS settings in Kali Linux.

4. VM Snapshots

   I learned that a clean snapshot should be created before performing risky or experimental activities.

  This provides a known-good recovery point for future cybersecurity exercises.

5. Documentation
   
   I learned that documenting commands, configuration, screenshots, problems, and solutions is an important part of a professional           cybersecurity project.

🔐 Security & Ethical Use
This laboratory is intended strictly for education purposes only.

🔗 Tools & Resources

7-Zip: https://7-zip.org/download.html

VirtualBox: https://virtualbox.org/wiki/Downloads

Kali Linux: https://kali.org/get-kali

👤 Author

Unzila

Cybersecurity Professional B082

LinkedIn: https://www.linkedin.com/in/unzila-tanveer-71144139b/

📌 Project Information

Program Name: Cybersecurity at Networkwalks | Week: 01 | Project: Cybersecurity & Pentesting Lab Setup | Repository: GitHub
