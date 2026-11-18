Windows Basics | TryHackMe
Project Overview
This project documents my hands-on experience with Windows Server 2019 through the TryHackMe Windows Basics room.
The lab focused on Windows system administration fundamentals, file management, system monitoring, and endpoint security.
A key exercise involved performing an antivirus scan, investigating a detected test file, and reviewing security alert details.
Lab Information
* Platform: TryHackMe
* Room: Windows Basics
* Operating System: Windows Server 2019
* Category: Windows Fundamentals and Endpoint Security
* Room Link: https://tryhackme.com/room/windowsbasics
Learning Objectives
* Navigate the Windows desktop, Start menu, and taskbar.
* Explore files and directories using File Explorer.
* Review system information and Windows settings.
* Understand application installation and updates.
* Monitor system activity using Task Manager.
* Explore Windows Security and Windows Defender Firewall.
* Perform an antivirus scan and examine a security detection.
Hands-On Security Investigation
Antivirus Detection Analysis
I used Windows Security to perform a custom antivirus scan of the lab’s onboarding directory.
The scan identified an EICAR antivirus test file.
Detection details:
* Threat name: Virus:DOS/EICAR_Test_File
* Alert severity: Severe
* Detection status: Quarantined
* Detection category: Virus
* Affected file: tryhatmemaldoc.txt
Investigation Process
1. Opened Windows Security.
2. Navigated to Virus & threat protection.
3. Selected the custom scan option.
4. Scanned the onboarding directory.
5. Reviewed the detected threat.
6. Opened the detection details.
7. Examined the affected file, scheduled task, and registry entries.
8. Confirmed the reported quarantine status.
Findings
The security alert identified a test file within the onboarding directory.
The affected items also included references to a Windows scheduled task and related registry entries.
This exercise demonstrated how Windows Security reports detected threats and provides information for further investigation.
The EICAR file was a harmless antivirus test file used for training. The exercise did not involve a confirmed real-world malware infection.
Windows Security Concepts
During this room, I studied:
* Antivirus scanning and detection
* Threat classification
* Quarantine status
* Security alert investigation
* Endpoint protection fundamentals
* Windows Firewall configuration concepts
* Windows scheduled tasks and registry references
Tools and Technologies
* Windows Server 2019
* Windows Security
* Microsoft Defender Antivirus
* Windows Defender Firewall
* Task Manager
* File Explorer
* Windows Settings
Relevance to SOC Analyst Work
This lab helped me practice reviewing an endpoint security alert and identifying affected system components.
These fundamentals support further learning in security monitoring, alert triage, endpoint investigation, and incident response.
Key Takeaways
I gained practical experience navigating a Windows environment, using built-in administrative tools, performing an antivirus scan, and examining threat detection details.
The investigation reinforced the importance of reviewing alert severity, detection status, file paths, and related system artifacts when assessing a security event.
Reference
TryHackMe Windows Basics
https://tryhackme.com/room/windowsbasics
