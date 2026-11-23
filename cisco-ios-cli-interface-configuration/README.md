# Cisco IOS CLI Modes, Interface Configuration and Troubleshooting

## Overview

This hands-on lab demonstrates basic Cisco IOS command-line navigation, IPv4 interface configuration, and interface status verification using Cisco Packet Tracer.

The objective is to understand the different IOS command modes, configure a network interface, and troubleshoot a basic interface activation issue.

## Lab Objectives

- Navigate between Cisco IOS command modes.
- Configure an IPv4 address and subnet mask on a router interface.
- Understand the purpose of the `no shutdown` command.
- Verify interface configuration and operational status.
- Identify and correct a basic interface configuration issue.

## Technologies and Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- IPv4
- Router interface configuration
- Basic network troubleshooting

## Cisco IOS Commands Practiced

| Command | Purpose |
|---|---|
| `enable` | Enter Privileged EXEC mode |
| `configure terminal` | Enter Global Configuration mode |
| `interface <interface>` | Enter Interface Configuration mode |
| `ip address <address> <subnet-mask>` | Assign an IPv4 address and subnet mask |
| `no shutdown` | Administratively enable an interface |
| `show ip interface brief` | Display interface IP addresses and operational status |
| `show running-config` | Display the current running configuration |

## Troubleshooting Demonstration

During this lab, an interface activation issue was intentionally introduced by leaving out the `no shutdown` command.

The `show ip interface brief` command was used to inspect the interface status and identify the issue.

After identifying the cause, the interface was enabled and its status was verified again.

This exercise demonstrates a basic troubleshooting workflow:

1. Observe the interface status.
2. Identify the configuration issue.
3. Apply the appropriate correction.
4. Verify the result.

## Practical Demonstration

The hands-on video demonstrates the lab execution, including:

- Cisco IOS command-line navigation
- Interface configuration
- Configuration verification
- Identification of the intentionally introduced issue
- Troubleshooting and correction

**Video:** [Watch the hands-on demonstration]([YOUR_VIDEO_LINK](https://lnkd.in/p/dgQmYHUF))

## Screenshots

Screenshots documenting the lab will be available in the `screenshots/` directory.

## Repository Contents

- `README.md` — Lab documentation
- `screenshots/` — Screenshots of the topology, configuration, and verification
- `configuration/` — Practiced commands and configuration notes
- `video/` — Link to the practical demonstration

## Key Learning Outcome

This lab strengthened my understanding of Cisco IOS command modes, router interface configuration, verification commands, and the importance of troubleshooting through observable network status rather than assumptions.
