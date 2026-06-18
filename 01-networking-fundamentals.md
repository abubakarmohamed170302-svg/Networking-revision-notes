# Networking Fundamentals

## What is Networking?

Networking is:

> the communication between devices.

Examples:

* laptop to router
* laptop to server
* server to server
* phone to website

Without networking:

```text id="3hmmtv"
No internet
No websites
No cloud
```

---

## Why Networking Matters

Networking allows:

* communication
* data transfer
* internet access
* cloud connectivity
* server management

DevOps uses networking constantly.

---

## What is a Network?

A network is:

> a group of connected devices.

Example:

```text id="qpd8nm"
Laptop
 ↓
Router
 ↓
Internet
 ↓
Server
```

---

## Types of Networks

### LAN

Local Area Network.

Small network.

Example:

```text id="rvh5rq"
Home
Office
```

Fast and local.

---

### WAN

Wide Area Network.

Large network.

Example:

```text id="8h6v7r"
The Internet
```

Connects multiple LANs.

---

## IP Address

An IP address is:

> a unique address for a device.

Think:

```text id="m5n1kp"
House address
```

Example:

```text id="3sj6os"
192.168.1.10
```

Without IP:

devices cannot find each other.

---

## Public vs Private IP

### Private IP

Used inside local network.

Example:

```text id="1jmhgt"
192.168.x.x
10.x.x.x
172.16.x.x
```

Not directly accessible from internet.

---

### Public IP

Given by ISP.

Used on internet.

Example:

```text id="vbjlwm"
82.45.x.x
```

Visible externally.

---

## MAC Address

A MAC address is:

> a physical hardware address.

Example:

```text id="f0j6du"
00:1A:2B:3C:4D:5E
```

Every device has one.

Think:

```text id="4fhcgs"
Device fingerprint
```

---

## Ports

Ports allow multiple services on one IP.

Common ports:

```text id="s5tdxv"
22   SSH
80   HTTP
443  HTTPS
53   DNS
25   SMTP
```

Very important.

---

## TCP vs UDP

### TCP

Reliable.

Checks data arrives.

Used for:

* websites
* SSH
* file transfers

---

### UDP

Faster.

No checks.

Used for:

* video streaming
* gaming
* DNS

---

## Basic Network Flow

Example:

```text id="bxn7dq"
Laptop
 ↓
Router
 ↓
DNS
 ↓
Website Server
 ↓
Response
```

This is how browsing works.
