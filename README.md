# PRODIGY_CS_05
This program employs the scapy module to intercept network data. It establishes a function named packet_callback, which is executed for every intercepted packet. This function verifies the packet's layers (IP, TCP, UDP, DNS) and retrieves pertinent details like the IP addresses of the sender and receiver, the ports used, the protocol in use, and the DNS query. To execute this program, ensure the scapy module is installed. It can be installed via pip install scapy. The program will intercept packets on the specified interface and display the packet details as they are received. The filter parameter determines which packets to intercept based on the protocol type (IP, TCP, UDP, DNS). The store parameter is set to False to avoid storing the packets in memory, which could be beneficial for observing real-time network activity.
