# 🔐 Operating System Security

## Description

**Operating System Security** introduces the fundamental concepts of securing operating systems, with a primary focus on Linux security and Secure Shell (SSH) authentication.

This room explores common security mechanisms used to protect operating systems, demonstrates secure remote access using SSH, and provides hands-on experience with authentication methods and best security practices.

---

## Objectives

- Understand the fundamentals of operating system security.
- Learn the importance of authentication and access control.
- Explore Secure Shell (SSH) for secure remote administration.
- Understand password-based and key-based SSH authentication.
- Apply basic operating system security best practices.

---

## Skills Learned

- Operating System Security Fundamentals
- Linux Security Basics
- Secure Remote Access (SSH)
- SSH Authentication
- User Authentication & Access Control
- Security Best Practices

---

## Tools Used

- Linux Terminal
- OpenSSH
- SSH Client

---

## Key Concepts

- Operating System Security
- Authentication
- Authorization
- Secure Shell (SSH)
- Password Authentication
- Public Key Authentication
- SSH Key Pairs
- Remote System Administration

---

## Key Commands

| Command | Description |
|---------|-------------|
| `ssh user@host` | Connect to a remote host using SSH |
| `ssh -i key.pem user@host` | Authenticate using a private key |
| `ssh-keygen` | Generate a new SSH key pair |
| `cat ~/.ssh/authorized_keys` | View authorized public keys |
| `chmod 600 key.pem` | Secure a private SSH key |
| `whoami` | Display the current user |
| `hostname` | Display the system hostname |

---

## Key Takeaways

- Operating system security is a critical component of cybersecurity.
- SSH provides encrypted communication for secure remote administration.
- Public key authentication is more secure than password authentication.
- Protecting private keys and enforcing proper permissions are essential security practices.
- Understanding authentication mechanisms lays the foundation for secure Linux administration and penetration testing.


---

## Disclaimer

This repository is intended for educational purposes only. All activities were performed within the authorized TryHackMe lab environment.
