# Networking Basics

## What Is Data Networking?

Data networking is the process of connecting computing devices to enable the exchange of data and the sharing of resources. A network allows devices to communicate using standardized protocols, ensuring reliable and efficient data transmission.

A computer network can consist of two devices connected together or millions of devices distributed across the world. Regardless of its size, every network follows the same fundamental principle: transmitting information from one device to another.

Examples of data exchanged over a network include:

- Web pages
- Emails
- Files
- Voice and video calls
- Database queries
- Cloud services

---

## Why Networking Matters

Modern organizations depend on computer networks for nearly every business operation. Networks enable users to communicate, collaborate, and access shared resources regardless of their physical location.

Common benefits of networking include:

- Resource sharing
- Internet access
- Centralized data storage
- Remote access
- Faster communication
- Cloud computing services
- Business continuity

From a cybersecurity perspective, networks represent both an opportunity and a risk. While they enable connectivity and collaboration, they also create potential attack surfaces that adversaries can exploit.

Understanding networking is therefore one of the most important prerequisites for cybersecurity professionals.

---

## Types of Networks

Networks are commonly classified according to the geographic area they cover.

### Personal Area Network (PAN)

A Personal Area Network connects devices within a very short distance, typically around a single user.

Examples include:

- Bluetooth headphones
- Smartwatches
- Wireless keyboards
- Mobile phones

Typical range:
- Less than 10 meters

---

### Local Area Network (LAN)

A Local Area Network connects devices within a limited area such as:

- Homes
- Offices
- Schools
- Campuses

Characteristics:

- High speed
- Low latency
- Privately managed
- Ethernet or Wi-Fi based

Examples:

- Office network
- Home Wi-Fi network

---

### Metropolitan Area Network (MAN)

A Metropolitan Area Network interconnects multiple LANs across a city or metropolitan area.

Examples:

- University campuses
- Government agencies
- City-wide ISP infrastructure

Characteristics:

- Covers an entire city
- Usually managed by service providers or large organizations

---

### Wide Area Network (WAN)

A Wide Area Network connects networks across large geographic distances.

Characteristics:

- Connects multiple LANs
- May span countries or continents
- Uses public and private communication links

The Internet is the largest WAN in existence.

---

## Common Network Components

Every network consists of hardware devices responsible for transmitting, receiving, and directing traffic.

### End Devices

Devices that generate or consume data.

Examples:

- Desktop computers
- Laptops
- Smartphones
- Servers
- Printers
- IoT devices

---

### Network Interface Card (NIC)

A Network Interface Card enables a device to communicate over a network.

Each NIC possesses a unique MAC (Media Access Control) address used for communication within a local network.

---

### Switch

A switch connects devices inside a Local Area Network.

It forwards Ethernet frames based on MAC addresses, allowing efficient communication between connected devices.

---

### Router

A router connects different networks together.

Its primary function is routing IP packets between networks and determining the best path for data transmission.

Routers commonly connect internal networks to the Internet.

---

### Wireless Access Point (WAP)

A Wireless Access Point provides wireless connectivity to devices using Wi-Fi standards.

It allows wireless devices to access a wired network without requiring physical Ethernet connections.

---

### Firewall

A firewall monitors and filters network traffic according to predefined security rules.

Firewalls represent one of the first lines of defense against unauthorized access.

---

## The OSI Reference Model

The Open Systems Interconnection (OSI) Model is a conceptual framework developed by ISO to standardize network communication.

Rather than treating communication as a single process, the OSI model divides it into seven logical layers.

| Layer | Name | Main Responsibility |
|-------|------|---------------------|
| 7 | Application | Provides network services to applications |
| 6 | Presentation | Data formatting, encryption, compression |
| 5 | Session | Session establishment and management |
| 4 | Transport | Reliable end-to-end communication |
| 3 | Network | Logical addressing and routing |
| 2 | Data Link | Frame delivery and MAC addressing |
| 1 | Physical | Transmission of raw bits over physical media |

The OSI model simplifies troubleshooting, protocol development, and security analysis by isolating network functions into independent layers.

---

## Networking and Cybersecurity

Networking knowledge is fundamental to cybersecurity because nearly every cyberattack involves network communication.

Security professionals rely on networking concepts to:

- Analyze network traffic
- Detect malicious communications
- Configure firewalls
- Investigate incidents
- Secure remote access
- Deploy intrusion detection systems
- Protect enterprise infrastructure

Without understanding networking, it becomes difficult to understand how attacks occur or how defensive technologies operate.

---

## Summary

Networking forms the foundation of modern computing and cybersecurity.

In this lesson, you learned:

- What computer networking is
- Why networks are essential
- The major types of networks
- The primary network devices
- The purpose of the OSI Reference Model
- The relationship between networking and cybersecurity

These concepts provide the foundation for understanding protocols, routing, network services, and security technologies covered throughout the CompTIA Security+ certification.