# Task 4: Firewall Configuration and Management

## Project Summary

This project demonstrates the setup and testing of fundamental firewall rules on Windows and Linux operating systems. [cite_start]The core objective was to configure rules to filter network traffic by blocking and allowing services on designated ports[cite: 4]. [cite_start]This exercise was completed as part of the Elevate Labs Cybersecurity Internship program[cite: 2].

---

## Implementation Details

The following steps were executed using Windows Defender Firewall .

1.  **Initial State Analysis**
    The existing firewall configurations were reviewed on both platforms to establish a baseline[cite: 8].

2.  **Rule Creation: Block Port 23 (Telnet)**
    An inbound rule was created to block all TCP traffic on port 23, the standard port for the insecure Telnet protocol.

    *Screenshot of the Windows Firewall rule:*
    
 ![SharedScreenshot01](https://github.com/user-attachments/assets/02e7b875-0ef2-4792-b85e-a99ad0efadf2)


   
4.  **Rule Verification**
    The list of active firewall rules was checked to confirm that the new policies were successfully applied.

    *Screenshot of the status:*
    ![SharedScreenshot1](https://github.com/user-attachments/assets/63fe0b59-1bbf-43a6-bf21-d95c78bbdd42)


5.  **System Restoration**
    After successful testing and documentation, the created rules were removed to restore the system's original firewall configuration.

---

## Firewall Functionality Explained

A firewall serves as a primary defense mechanism for a network by monitoring and controlling incoming and outgoing traffic based on a defined set of security rules. It establishes a barrier between a trusted internal network and untrusted external networks.

Firewalls filter traffic based on several criteria, including:
* **IP Addresses:** Permitting or denying connections from specific source or destination IP addresses.
* **Port Numbers:** Controlling access to services by managing the ports they operate on, such as blocking Telnet (23).
* **Protocols:** Differentiating between and applying rules to various traffic types, such as TCP, UDP, and ICMP.
