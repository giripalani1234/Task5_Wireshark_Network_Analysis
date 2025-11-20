# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets and identify basic protocols and traffic types using Wireshark.

## Steps Performed
- Installed and launched Wireshark.
- Captured packets on my active interface.
- Generated traffic (ping, website browsing).
- Saved the session (.pcapng and filtered files).
- Filtered and analyzed protocols: ICMP, TCP, DNS, ARP, TLS, UDP.
- Took screenshots of relevant Wireshark filters and packet details.

## Identified Protocols
- **ICMP:** Packet type for ping commands.
- **TCP:** Used for web browsing and multiple connections.
- **DNS:** Domain name lookups for browsing or pinging.
- **ARP:** Address Resolution Protocol traffic observed in the capture.
- **TLS:** Encrypted web traffic when visiting HTTPS sites.
- **UDP:** Detected during DNS or other sessions.

## Packet Analysis Summary
- An ICMP Echo Request/Reply was identified during the ping test.
- DNS queries and responses were captured during web browsing.
- TCP packets showed handshake and data transport activity.
- TLS packets verified secure browsing traffic.
- ARP and UDP packets visible as base network functions.

## How Wireshark Helps Troubleshooting
Wireshark allows detailed inspection of live network traffic, helping identify issues, validate protocols and connections, and diagnose problems by viewing packet content and timing.

## Files Included
- `task5_capture.pcapng` – Full traffic capture
- Protocol-specific filtered captures (see filenames)
- Relevant screenshots (see image files)

## Submission
Repository link: [your GitHub repo URL]

