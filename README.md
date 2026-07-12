# CSCE 3530 Final Project
## Small Virtual LAN using GNS3

### Student
Hamza Shakur

### Instructor
Ali Zarafshani

### Course
CSCE 3530 – Introduction to Computer Networks

### Semester
Summer 2026

---

## Project Description

This project demonstrates the design and implementation of a small virtual Local Area Network (LAN) using GNS3 and Ubuntu Linux.

The Ubuntu virtual machine functions as a router and server providing:

- DHCP
- DNS
- NAT
- Apache HTTP Web Server

Two virtual client PCs communicate through an Ethernet switch while accessing local network resources and the Internet.

---

## Network

Subnet

```
192.168.10.0/24
```

Router

```
192.168.10.1
```

PC1

```
192.168.10.20
```

PC2

```
DHCP
```

---

## Services

- DHCP
- DNS
- NAT
- Apache2 HTTP Server

---

## Testing Performed

✔ DHCP lease

✔ DNS resolution

✔ NAT

✔ Internet connectivity

✔ ICMP

✔ HTTP server

✔ Packet capture using tcpdump

---

## Repository Structure

```
Documentation/
Configurations/
GNS3_Project/
Screenshots/
```

---

## Technologies Used

- GNS3
- Ubuntu Linux
- dnsmasq
- Apache2
- iptables
- tcpdump
- VPCS

---

## Project Status

Completed
