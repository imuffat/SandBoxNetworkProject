### Hello i'm Itoro Muffat

## Connect with Me
<a href="(https://www.linkedin.com/in/itoro-muffat-1b520554/)"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

### Brief Introduction

A dedicated cybersecurity student(M.Sc) with  a profound interest in technology and a dedication to solving complex problems. I have foundational knowledge of network security, Cyber Risk Management Frameworks, and data protection. Learning to be Proficient in basic tools and technologies like firewalls, antivirus software, and penetration testing frameworks, Linux Ubuntu distribution, Debian flavor. I am committed to continuous learning, staying updated on emerging threats, and mastering best practices in securing systems and data.

### Objective
My journey in computer Electronics and Technology has led me to develop a passion for cybersecurity, and I am now eager to transition into this field, specifically aiming to join a Security Operations Center (SOC) as a Tier 1 Analyst and a network forensic expert.



### Skills Learned
Build/design a sandbox network in GNS3 and Packet tracer.
Configured the very components of the sandbox network to communicate and exchange packets using Virtualbox.
Learning to analyze and interpret network logs using the Zabbix server and Wireshark.
Learning about Encryption and Decryption using RSA and AES standards. Also learned about the Hash functions, MD5, and SHA256
Ability to generate and recognize attack signatures and patterns.
Learning to build up my knowledge of network protocols and security vulnerabilities.
Use of SSH to remotely manage the server.
Development of critical thinking and problem-solving skills in cybersecurity.


### Tools Used

VirtualBox
Ubuntu Desktop 22.04(Management)
Ubuntu Server 22.04(Gateway Router)
Bitnami Opencart(Webserver)
Security Information and Event Management (SIEM) system for log ingestion and analysis.
Network analysis tools (such as Wireshark) are used to capture and examine network traffic.
Telemetry generation tools to create realistic network traffic and attack scenarios.


### Steps to Creating a Sandbox Network

I have outlined my step-by-step implementation of a sandboxed network using VirtualBox. The network has three VMs: a Desktop VM(Ubuntu Desktop - v22.04), a Gateway VM(Ubuntu Server 22.04), and an Application VM(Bitnami Opencart) which is configured in a private sandboxed environment to ensure the network is secure and in isolated communication.
I set my assigned static IP ranges to the subnets and gateways. I selected **192.168.23.2** for my Desktop VM, **192.168.23.1** for the gateway VM interface card acting as the default gateway for the desktop, **192.168.123.1** for the gateway VM interface card acting as the default gateway for the Application VM(Bitnami Opencart), and **192.168.123.3** for my Application VM. For internet access, I also configured NAT on a third interface card on my gateway server.

Below are the three VMs I used for my sandbox network:
-	Desktop VM: Ubuntu Desktop(22.04)
-	Gateway VM: Ubuntu Server(22.04)
-	Application VM: Bitnami OpenCart <br><br/>

Network Diagram designed from packet tracer.

![Network Diagram](Screenshots/NetworkDiagram.png) <br><br/>

IPTable

![IPTable](Screenshots/IPTable.png) <br><br/>


<figure>
  <video width="640" height="360" controls>
    <source src="Screenshots/Portfolio_2_Network_and_Security_Practices_Screen_cast1.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <figcaption>Browsing to OpenCart WebServwer </figcaption>
</figure>
