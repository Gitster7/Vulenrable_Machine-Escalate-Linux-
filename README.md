# Vulnerable_Machine(Linux)

An intentionally developed Linux vulnerable virtual machine.The main focus of this machine is to learn Linux Post Exploitation (Privilege Escalation) Techniques.

A Linux vulnerable virtual machine contains different features as.

12+ ways of Privilege Escalation
Vertical Privilege Escalation
Horizontal Privilege Escalation
Multi-level Privilege Escalation

## What is Privilege Escalation?

Privilege escalation can be defined as an attack that involves gaining illicit access of elevated rights, or privileges, beyond what is intended or entitled for a user. This attack can involve an external threat actor or an insider. Privilege escalation is a key stage of the cyberattack chain and typically involves the exploitation of a privilege escalation vulnerability, such as a system bug, misconfiguration, or inadequate access controls. In this blog, I will explain how privilege escalation works, the key attack vectors involved with privilege escalation, and the critical privileged access security controls you can implement to prevent or mitigate it.

## Vertical vs Horizontal Privilege Escalation

Privilege escalation attacks can be separated into two broad categories—horizontal privilege escalation and vertical privilege escalation. Often confused with each other, these terms are can be differentiated as follows:

Horizontal privilege escalation involves gaining access to the rights of another account—human or machine—with similar privileges. This action is referred to as “account takeover.” Typically, this would involve lower-level accounts (i.e. standard user), which may lack proper protection. With each new horizontal account compromised, an attacker broadens their sphere of access with similar privileges.
Vertical privilege escalation, also known as a privilege elevation attack, involves an increase of privileges/privileged access beyond what a user, application, or other asset already has. This entails moving from a low-level of privileged access, to a higher amount of privileged access. Achieving vertical privilege escalation could require the attacker to perform a number of intermediary steps (i.e. execute a buffer overflow attack, etc.) to bypass or override privilege controls, or exploit flaws in software, firmware, the kernel, or obtain privileged credentials for other applications or the operating system itself. In 2020, elevation of privilege vulnerabilities comprised 44% of all Microsoft vulnerabilities, according to the Microsoft Vulnerabilities Report 2021.

## Virtual Machine

Format: Virtual Machine (Virtualbox - OVA)
Operating System: Linux

## Networking

DHCP service: Enabled
IP address: Automatically assign
