# Task 5 - Capture and Analyze Network Traffic Using Wireshark

## Objective

To capture live network packets and analyze network protocols using Wireshark.

## Tools Used

- Wireshark
- Windows Command Prompt

## Procedure

1. Installed Wireshark.
2. Started packet capture on active network interface.
3. Generated traffic by browsing websites and pinging Google.
4. Captured packets for approximately one minute.
5. Applied protocol filters.
6. Analyzed packet details.

## Protocols Identified

### DNS
Purpose: Resolves domain names into IP addresses.

Example:
Query for google.com

### TCP
Purpose: Reliable connection-oriented communication.

Example:
TCP handshake packets observed.

### ICMP
Purpose: Network diagnostics and testing.

Example:
Ping request and reply packets.

### TLS/HTTPS
Purpose: Secure encrypted web communication.

Example:
HTTPS traffic generated while browsing websites.

## Findings

- DNS queries were generated before accessing websites.
- TCP packets established reliable connections.
- ICMP packets confirmed network connectivity.
- TLS packets showed encrypted web communication.

## Conclusion

Wireshark successfully captured and analyzed live network traffic. Multiple protocols including DNS, TCP, ICMP and TLS were identified and examined.
