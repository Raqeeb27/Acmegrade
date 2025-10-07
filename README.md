# ACMEGRADE Internship Final Assessment
## Hack into Windows Machine using Metasploit

This repository contains the final project assessment report from the **Acmegrade Internship, May 2024**. The project successfully demonstrated a controlled penetration test scenario to exploit a vulnerable Windows 7 machine using the *Metasploit Framework*.

## 🎯 Project Aim

The primary objective of this project was to gain remote access to a **Windows 7** machine (victim) from a **Kali Linux** machine (attacker) by leveraging the **Metasploit Framework** and a **Meterpreter** payload.

## 🛠️ Tools and Technologies Used

| Category | Tool/Technology | Role in Project |
| :--- | :--- | :--- |
| **Attacker OS** | Kali Linux | The penetration testing machine. |
| **Target OS** | Windows 7 | The victim machine that was compromised. |
| **Exploitation** | Metasploit Framework | Used to set up the listener (`multi/handler`) and manage the remote session. |
| **Payload Generation** | `msfvenom` | Used to generate the custom, malicious executable (`venom.exe`). |
| **Delivery Mechanism** | Python `http.server` | Used to quickly host and transfer the payload (`venom.exe`) to the target machine over port `8080`. |

