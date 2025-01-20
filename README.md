# Network Traffic Analysis with Wireshark

## **Project Overview**
This project involves capturing and analyzing network traffic using Wireshark, a popular packet-capturing tool. The goal is to understand the flow of network data, identify protocol distributions, and detect any potential anomalies in the traffic. This project is an essential skill for cybersecurity professionals, particularly those in blue team roles.

---

## **Features**
- Capturing live network traffic.
- Filtering and analyzing packets based on protocols such as HTTP, TCP, and DNS.
- Observing communication patterns between endpoints.
- Detecting suspicious activities like unusual DNS queries or unexpected data transfers.

---

## **Tools and Technologies**
- **Wireshark**: A network protocol analyzer for capturing and inspecting network traffic.
- **Operating System**: Tested on Windows, but Wireshark is cross-platform.

---

## **Installation and Setup**
1. Download and install Wireshark from [Wireshark Official Website](https://www.wireshark.org/).
2. Ensure you have administrative privileges to capture live traffic.
3. Close unnecessary applications to reduce background noise during traffic capture.

---

## **Steps to Execute the Project**
1. **Start Wireshark**:
   - Open Wireshark and select the active network interface (e.g., Wi-Fi or Ethernet).
   - Click the green "Shark Fin" icon to start capturing traffic.

2. **Capture Traffic**:
   - Perform activities like browsing websites, running applications, or streaming content to generate network traffic.
   - Stop the capture after a few minutes by clicking the red square icon.

3. **Apply Filters**:
   - Use filters to focus on specific traffic types:
     - HTTP: `http`
     - DNS: `dns`
     - TCP: `tcp`
     - IP Address: `ip.addr == <IP>`

4. **Analyze Packets**:
   - Observe protocols, source/destination IPs, and payload details.
   - Use the Statistics menu for insights like protocol hierarchy and endpoint activity.

5. **Document Findings**:
   - Take screenshots of notable traffic patterns or anomalies.
   - Prepare a report summarizing protocol distribution and suspicious activities.

---

## **Findings**
- **Protocol Distribution**:
  - HTTP: 60% (web browsing traffic).
  - DNS: 20% (domain resolution).
  - TCP: 15% (general communication).
  - Other Protocols: 5% (e.g., ARP).

- **Suspicious Activities**:
  - Unusual DNS queries resolving random domain names.
  - High data transfer to an external IP from an unexpected geographic location.

---

## **Conclusion**
This project highlights the importance of network traffic monitoring in identifying and mitigating potential security threats. By analyzing traffic patterns and filtering suspicious packets, security analysts can gain valuable insights into network behavior and enhance defensive measures.

---

## **How to Use This Project**
1. Clone this repository to your local machine:
   ```bash
   git clone <repository-url>
   ```
2. Follow the steps mentioned above to replicate the project.
3. Customize the filters and traffic analysis to suit your environment.

---

## **Contributing**
Contributions are welcome! If you have improvements or suggestions, feel free to submit a pull request or open an issue.

---

## **Acknowledgments**
- Wireshark for providing an exceptional tool for network analysis.
- Online resources and tutorials for supporting this learning experience.
