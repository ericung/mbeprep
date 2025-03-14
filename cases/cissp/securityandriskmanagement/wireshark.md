To capture the `ping` command (ICMP packets) in Wireshark, follow these steps:

1. **Start Wireshark:**
   - Open Wireshark and select the network interface you want to monitor (e.g., Ethernet, Wi-Fi).

2. **Set a Capture Filter (Optional):**
   - To focus only on ICMP packets, use the capture filter `icmp`. This ensures you only capture ping-related traffic.

3. **Begin Capturing:**
   - Click the green shark fin icon to start capturing packets.

4. **Run the Ping Command:**
   - Open your terminal or command prompt and execute the `ping` command. For example:
     ```bash
     ping -c 4 google.com  # Linux/macOS
     ping -n 4 google.com  # Windows
     ```
     This sends 4 ICMP Echo Request packets to the specified host.

5. **Stop the Capture:**
   - Once the ping command completes, return to Wireshark and click the red square icon to stop capturing.

6. **Analyze the Packets:**
   - Look for ICMP packets in the captured data. You can use the display filter `icmp` to isolate them. You'll see Echo Request and Echo Reply packets, along with details like source/destination IPs and round-trip times.

If you need help interpreting the results or setting up filters, let me know! 😊


