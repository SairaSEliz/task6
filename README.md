# task6
 captured ICMP packets in Wireshark
 
##Open Wireshark:

1***Launch Wireshark from the terminal or application menu.***
---You can open it from the terminal by typing wireshark.
---Start Capturing Packets:

2***In Wireshark, select the network interface eth0 from the list of available interfaces. Click on it to start capturing packets.***
---Ping Google:

ping -c 4 google.com

3***Observe Captured Packets:***

---Switch back to Wireshark and observe the packet capture. Filter by ICMP to focus on the ICMP packets:
---In the display filter bar, type icmp and press Enter.
---Verify that there are four ICMP requests (Echo Requests) and four ICMP responses (Echo Replies).

4***Save the Capture:***

----Stop the capture in Wireshark by clicking on the stop button (red square) in the toolbar.
----Save the capture file by going to File -> Save As, then choose the file format pcapng and name it ping.pcapng
