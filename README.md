 Network-Traffic-Analyzer:
 This code creates a basic network traffic analyzer using Python and Scapy. It captures network packets on a specified interface (eth0 by default) using the sniff_packets method. For each packet, it extracts the source and destination IP addresses and updates the packet count for each IP address in the packet_counts dictionary.

After capturing packets, it generates a bar plot using Matplotlib to visualize the top 10 traffic sources based on packet count. The plot_traffic method sorts the packet_counts dictionary by packet count and plots the top 10 traffic sources.

To use this code, you'll need to install Scapy (pip install scapy) and Matplotlib (pip install matplotlib). Additionally, you may need to run the script with administrator privileges to capture network packets.
