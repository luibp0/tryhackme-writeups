# OSI Model

## Overview

This room introduces the **OSI (Open Systems Interconnection) Model**, a framework used to understand how data travels across a network.

The OSI Model divides network communication into **seven layers**, with each layer having a specific role in transmitting and receiving data between devices.

## Objectives

* Understand the purpose of the OSI Model.
* Learn the seven layers of the OSI Model.
* Understand how data moves through each layer.
* Learn the role of protocols and network devices at different layers.
* Understand encapsulation and decapsulation.

## The 7 OSI Layers

| Layer | Name         | Main Function                                             |
| ----- | ------------ | --------------------------------------------------------- |
| 7     | Application  | Provides network services to applications                 |
| 6     | Presentation | Translates, encrypts, and formats data                    |
| 5     | Session      | Establishes and manages communication sessions            |
| 4     | Transport    | Handles data delivery using protocols such as TCP and UDP |
| 3     | Network      | Handles routing and IP addressing                         |
| 2     | Data Link    | Handles MAC addresses and frames                          |
| 1     | Physical     | Transmits raw bits through physical media                 |

## Skills Learned

* OSI Model fundamentals
* Understanding network layers
* TCP and UDP basics
* IP addressing concepts
* MAC addressing
* Network communication
* Encapsulation and decapsulation

## Tools Used

* TryHackMe Learning Platform
* Web Browser

## Key Takeaways

* The OSI Model consists of seven layers.
* Each layer performs a specific function during network communication.
* Data moves from Layer 7 down to Layer 1 when being sent.
* The receiving device processes the data from Layer 1 back up to Layer 7.
* TCP and UDP operate at the Transport Layer.
* IP addressing and routing operate at the Network Layer.
* MAC addresses and frames are associated with the Data Link Layer.
* Understanding the OSI Model is essential for networking and cybersecurity fundamentals.

## Reflection

This room helped me understand how network communication is organized using the OSI Model. Learning the seven layers made it easier to understand how data moves between devices and how different protocols and network technologies work together.

Understanding the OSI Model provides a strong foundation for networking and cybersecurity, especially when analyzing network traffic, troubleshooting connectivity issues, and learning about network-based attacks and defenses.

---

> **Note:** Personal learning notes only. No flags, answers, or complete walkthroughs are included.
