# Secure Chat System - Cyber Security Mini Project

## ## Project Overview
This project is a secure, C++ based communication platform designed to demonstrate the fundamentals of **Network Security** and **Cryptography**. The system establishes a protected channel between a `client.cpp` and `server.cpp`, ensuring that all exchanged data remains confidential and integral, even if intercepted on the network.

---

## ## Key Security Features

### ### User Identity & Access Management
* **Secure Registration** – Users can create unique profiles with a username and password.
* **Password Hashing** – To ensure **Confidentiality**, passwords are never stored in plain text. Instead, they are processed through a secure hashing algorithm before storage.
* **Robust Authentication** – The system verifies users by comparing the hash of the entered password against the stored credential database.

### ### Encrypted Communication Channel
* **End-to-End Encryption** – All messages are encrypted on the sender's side before being transmitted over the network.
* **Traffic Protection** – The encryption ensures that unauthorized parties or packet sniffers cannot read the conversation.
* **Data Integrity** – Prevents "Man-in-the-Middle" (MitM) attacks from easily altering the message content during transit.

### ### Secure Credential Storage
* **Database Protection** – User data is stored in a format that maintains privacy.
* **Linux Optimized** – Developed and tested in a Linux environment to leverage native networking libraries.

---

## ## Technical Implementation

| Component | Specification |
| :--- | :--- |
| **Language** | C++ |
| **Environment** | Linux (Ubuntu/Debian recommended) |
| **Networking** | Socket Programming (Client-Server Architecture) |
| **Security Focus** | Hashing, Encryption, and Access Control |
| **Verification** | Verified via **Wireshark** Packet Analysis |

---

## ## Testing & Validation
To confirm the effectiveness of the security measures, the system was tested using **Wireshark**:
- **Result:** Network traffic analysis confirmed that all message payloads were unreadable (encrypted) during transmission.
- **Verification:** Successfully validated that no plain-text passwords or messages were leaked over the network interface.

---

## ## Author  
**Irtaza Zahid** 
*Cyber Security Student & Developer*  
*Focused on building secure digital communication and defensive programming.*  
