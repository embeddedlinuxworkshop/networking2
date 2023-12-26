# Exercise: Analyzing Communication Between Two Machines

## Objective:

### Capture and analyze communication between two machines on a local network.
Setup:

#### Have two machines connected to the same local network (it can be a home network or a lab environment).
Steps:
a. Install Wireshark on both machines.

b. Choose one machine as the sender and the other as the receiver.

c. On the sender machine, open Wireshark and start capturing packets on the network interface connected to the local network.

d. On the receiver machine, start Wireshark and do the same.

e. Have the sender machine initiate some network activity, such as pinging the IP address of the receiver or accessing a shared folder.

f. Stop the packet capture on both machines after a short period.

#### Analysis:

Load the captured packets in Wireshark on each machine.

Apply a display filter to show only traffic between the two machines. You can use the filter ip.addr == [sender_IP] && ip.addr == [receiver_IP], replacing [sender_IP] and [receiver_IP] with the actual IP addresses.

Identify the source and destination IP addresses, as well as the ports used.

Analyze the sequence of packets exchanged between the machines.

#### Questions to Consider:

What types of packets are exchanged between the two machines?

Can you identify the protocol used in the communication?

Are there any errors or retransmissions in the communication?







