# wireshark
Captured live network traffic using Wireshark, analyzed TCP, DNS, UDP, and other protocols, and documented findings.
# Network Traffic Capture & Protocol Analysis Using Wireshark

## Objective
To capture live network traffic using Wireshark, identify common network protocols, and analyze captured packets as part of the cybersecurity internship Task 5.

---

## Tools Used
| Tool | Purpose |
|------|---------|
| Wireshark | Live packet capturing and protocol analysis |
| Web Browser / Ping | To generate network traffic |

---

## Steps Performed

### Step 1: Installed Wireshark
- Downloaded and installed Wireshark (including Npcap) to enable packet capturing.

### Step 2: Started Live Capture
- Opened Wireshark and selected the active network interface (Wi-Fi).
- Started packet capture.

###  Step 3: Generated Traffic
- Opened websites and/or used the command `ping firefox.com` to generate DNS, TCP, and ICMP traffic.

###  Step 4: Stopped and Saved Capture
- Stopped the capture.
- Saved the file as `capture.pcapng`.

###  Step 5: Applied Protocol Filters
Tested the following Wireshark filters:
| Filter | Protocol Identified |
|--------|---------------------|
| `tcp`  | Transmission Control Protocol |
| `udp`  | User Datagram Protocol |
| `dns`  | Domain Name System |

## Files Included
1. Live traffic being captured
2. DNS filter applied (`dns`)
3. TCP packet details view
4. UDP packet details view 

## Learning Outcome
✔ Understood packet capturing using Wireshark  
✔ Identified common protocols: TCP, UDP, DNS, ICMP  
✔ Learned how to filter and analyze packets  
✔ Interpreted traffic flow between source and destination  


