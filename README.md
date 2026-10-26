# NetworkWalks Week 1 — Cybersecurity & Pentesting Lab Setup

> **Internship task:** WK1-PM1  
> **Focus:** VirtualBox, Kali Linux, NAT networking, and connectivity testing

## About the Project

This repository documents my Week 1 lab-setup task for the NetworkWalks Cybersecurity Internship. The goal is to prepare a virtual environment for cybersecurity and ethical-hacking practice using Oracle VirtualBox and Kali Linux.

## Objectives

- Set up a Kali Linux virtual machine in VirtualBox.
- Create a NAT Network using the required `10.0.0.0/24` subnet.
- Configure and inspect the virtual machine's network settings.
- Test network connectivity.
- Keep screenshots as evidence of the setup process.

## Tools Used

| Tool | Purpose |
|---|---|
| Oracle VirtualBox | Runs the virtual machine |
| Kali Linux | Cybersecurity testing environment |
| Linux terminal | Network inspection and connectivity tests |

## Lab Network

| Setting | Required value |
|---|---|
| NAT Network name | `NatNetwork` |
| IPv4 prefix | `10.0.0.0/24` |
| Required Kali IPv4 address | `10.0.0.2/24` |

The screenshots currently included document the VirtualBox VM, NAT Network settings, a successful ping to `8.8.8.8`, and the Kali Linux desktop. The static IP, DNS resolution, shared-folder integration, clipboard/drag-and-drop, and snapshot should be marked complete only after they have been verified.

## Screenshots

Upload your four screenshots to a folder named `screenshots/` in this repository and use these filenames (or update the links below to match your actual filenames):

### 1. VirtualBox VM Details

![VirtualBox VM details](screenshots/01-virtualbox-vm.png)

### 2. NAT Network Configuration

![NAT Network configuration](screenshots/02-nat-network.png)

### 3. Internet Connectivity Test

![Ping test to 8.8.8.8](screenshots/03-internet-connectivity.png)

### 4. Kali Linux Desktop

![Kali Linux desktop](screenshots/04-kali-desktop.png)

## Verification Checklist

- [x] VirtualBox VM created and running
- [x] NAT Network created with `10.0.0.0/24`
- [x] Ping to `8.8.8.8` succeeded in the captured test
- [ ] Kali IPv4 address verified as `10.0.0.2/24`
- [ ] `ping -c 4 google.com` verified
- [ ] Shared host Downloads folder tested from Kali
- [ ] Shared Clipboard set to Bidirectional
- [ ] Drag and Drop set to Bidirectional
- [ ] VM snapshot created

## What I Learned

This task gave me practice with virtual machines, NAT networking, Linux network commands, and basic connectivity troubleshooting. I will add further evidence as I complete and verify the remaining configuration items.

## Internship

**Program:** NetworkWalks Cybersecurity Internship  
**Task:** Week 1 — Project Module 1 (WK1-PM1)

---

*This README reflects the evidence captured so far. Checklist items that are not yet verified remain unchecked.*
