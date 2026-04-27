# Linux Network Tracing Lab

## Objective
Analyze how traffic travels across networks and identify where latency or routing changes occur using traceroute and tracepath.

---

## Lab Overview
In this lab, I examined how data moves from my system to external services. I compared routing paths using both domain names and direct IP addresses to understand how network behavior can vary.

## Screenshots

### Step 1: Install traceroute
![Step 1](./screenshots/step1-install-traceroute.png)

### Step 2: Traceroute to domain
![Step 2](./screenshots/step2-traceroute-domain.png)

### Step 3: Traceroute to IP
![Step 3](./screenshots/step3-traceroute-ip.png)

### Step 4: Tracepath output
![Step 4](./screenshots/step4-tracepath.png)
---

## Tools Used
- Ubuntu (Virtual Machine)
- traceroute
- tracepath
- ping

---

## Steps Performed

### 1. Installed traceroute
```bash
sudo apt update
sudo apt install traceroute -y
