# 🏖️ Beach Bar

## Description

**Beach Bar** introduces a real-world application security scenario where a vulnerable playlist import feature becomes the entry point for exploitation. The room focuses on identifying insecure deserialization and unsafe file parsing practices that can ultimately lead to remote code execution.

---

## Objectives

- Analyze the application's import functionality.
- Investigate how YAML files are processed.
- Understand the risks of insecure deserialization.
- Identify opportunities for command execution.
- Gain shell access through application misconfiguration.

---

## Skills Learned

- Web Application Security
- YAML Deserialization
- Remote Code Execution (RCE)
- Payload Development
- Linux Command Execution
- Exploit Analysis

---

## Tools Used

- Burp Suite
- Linux Terminal
- YAML
- Python
- Netcat
- Browser Developer Tools

---

## Key Takeaways

- Deserializing untrusted data can introduce critical security vulnerabilities.
- Improper validation of uploaded files may lead to arbitrary code execution.
- Understanding serialization formats is essential for identifying application weaknesses.
- Secure input validation and safe parsers are critical to preventing exploitation.

---

## Disclaimer

This write-up is intended for educational purposes only. All activities were performed within the authorized TryHackMe lab environment.
