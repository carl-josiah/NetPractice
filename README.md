*This project has been created as part of the 42 curriculum by **ccastro**.*

# NetPractice

## Description

**NetPractice** is a networking project from the 42 curriculum designed to teach the fundamentals of computer networking through a series of interactive exercises.

The objective of the project is to understand how devices communicate across networks by configuring IP addresses and subnet masks to establish successful connections between hosts. Throughout the levels, the project introduces essential networking concepts such as IPv4 addressing, subnetting, routing, gateways, switches, and packet delivery.

Rather than writing code, NetPractice focuses on reasoning about network topologies and configuring each device correctly so packets can travel from their source to their destination.

### What I learned

Working through NetPractice helped me develop a much stronger understanding of:

* IPv4 addressing
* Subnet masks and subnetting
* Network and host portions of an IP address
* Packet routing between networks
* Default gateways
* Routers and switches
* Basic network troubleshooting

One of the most important concepts that clicked for me was understanding how IP addresses allow devices and routers to determine where packets should be delivered. Once I understood how subnet masks separate the network portion from the host portion of an address, it became much easier to determine which devices could communicate directly and when a router was required.

The most challenging part of the project was understanding subnet masks and subnetting and especially learning how to divide networks into smaller subnets and determine which IP addresses were valid within each subnet. These concepts became much clearer after solving many different scenarios and understanding *why* a particular configuration worked instead of simply memorizing the answers.

---

## Instructions

### Running NetPractice

From the downloadable file (net_practice.1.9.tgz), launch the training interface using:

```bash
./run.sh
```

The exercises were completed using **Google Chrome**, although any modern browser should work.

### Exporting configurations

After successfully completing a level:

1. Click **Get Config**.
2. Save the exported configuration file.
3. Repeat this process for every level.

### Submission

The repository root must contain:

* `README.md`
* `run.sh`
* **10 exported configuration files**, one for each completed level.

Example repository structure:

```text
.
├── README.md
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
└── level10.json
```

---

## Advice for Future Students

Take your time with each level.

It is easy to become overwhelmed by trying to understand every networking concept at once. Instead, focus on one question at a time. If something doesn't make sense, ask yourself the first question that comes to mind and answer that before moving on.

Networking concepts build upon one another. Once you understand a single idea, such as subnet masks or how routers forward packets, the later levels become much easier.

Most importantly, keep practicing. Repetition is what makes the concepts stick.

---

## Resources

### Official & Reference Material

* RFC 791 – Internet Protocol (IPv4)
* RFC 950 – Internet Standard Subnetting Procedure
* Cisco Networking Academy
* IBM Documentation – OSI Model
* Cloudflare Learning Center – Networking

### Community Resources

* https://github.com/lpaube/NetPractice
* Various YouTube tutorials covering NetPractice, subnetting, and introductory networking concepts.

### Networking Concepts Studied

This project covers the following networking concepts:

* TCP/IP addressing
* IPv4 addressing
* Subnet masks
* Subnetting
* Network and host portions of an address
* Default gateways
* Routers
* Switches
* Packet routing
* Network topology
* OSI model
* Basic network troubleshooting

### AI Usage

AI was used as a learning tool throughout this project.

Its primary purpose was to reinforce my understanding of networking concepts rather than provide direct solutions. I used AI to:

* Explain networking concepts in simpler terms.
* Better understand subnetting and subnet masks.
* Explain why a particular IP address or subnet mask was correct instead of another.
* Clarify routing decisions and packet delivery.
* Answer conceptual questions that arose while solving the levels.
* Improve the wording and organization of this README.

The actual understanding of the project came from repeatedly solving the exercises, experimenting with different configurations, and reasoning through each networking scenario until the concepts became intuitive.

