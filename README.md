Packet Sniffer Project

Table of Contents





Description



Features



Technologies Used



Installation



Usage



Screenshots



Examples



Ethical Use



Contributing



License



Contact

Description

This project is a Python-based packet sniffer that captures and analyzes network traffic. It helps users understand network protocols and monitor data packets, useful for learning network security concepts.

Features





Captures live network traffic



Filters packets by protocol (e.g., TCP, UDP)



Displays packet details (source/destination IP, protocol, payload)



Saves captured packets to a file

Technologies Used





Python 3



Scapy library



Wireshark (for validation)

Installation





Clone the repository:

git clone https://github.com/yourusername/packet-sniffer.git



Install dependencies:

pip install scapy



Ensure administrative privileges for packet capture (may require sudo on Linux).

Usage

Run the script with administrative privileges:

sudo python packet_sniffer.py

Filter for TCP packets:

sudo python packet_sniffer.py --filter "tcp"

Screenshots

Captured packets displayed in the terminal.

Examples

Capture 10 packets:

sudo python packet_sniffer.py --count 10

Example output:

Packet 1: Source IP: 192.168.1.1, Destination IP: 192.168.1.2, Protocol: TCP
...

Ethical Use

This tool is for educational purposes only. Do not use it on networks or systems without explicit permission. The author is not responsible for misuse.
