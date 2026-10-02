# Snort-Lab-IDS-IPS-
  <img src="01.jpg" alt="Snort Logo" width="300" style="border-radius:10px; border:2px solid #ccc;"/>

### Snort is a powerful open-source network intrusion detection and prevention system (IDS/IPS).
<img width="474" height="258" alt="02" src="https://github.com/user-attachments/assets/50dda323-2bc7-405d-9600-1329e4d4ed06" />

It can be used for real-time traffic analysis, packet logging, and detecting a wide range of malicious activities on your network.
## Here’s a breakdown of its key features:
## Capabilities:

- **Packet Capture:** Like a tcpdump, Snort can capture network traffic, allowing you to analyze individual packets for suspicious content.

- **Protocol Analysis:** Snort understands various network protocols and can dissect their contents to identify potential threats.

- **Content Matching:** Snort uses a rule-based system to compare network traffic against predefined rules that flag malicious activity. These rules can target specific protocols, payloads, or network anomalies.

- **Alerting & Logging:** Snort generates alerts when it detects suspicious activity, notifying you of potential threats. It can also log traffic for analysis and forensic investigation.

- **Intrusion Prevention (Optional):** In addition to detection, Snort can be configured to actively block identified threats by dropping packets or redirecting them.
## Deployment:
- **Packet Sniffer:** For passive monitoring and traffic analysis.
- **IDS:** Alerts about suspicious activity but doesn’t actively block threats.
- **IPS:** Actively blocks identified threats based on predefined rules.
## Benefits:
- **Open-source & Free:** Accessible to individuals and organizations of all sizes.
- **Highly Customizable:** Rule-based system allows for tailoring Snort to your specific needs and threats.
- **Lightweight & Efficient:** Runs effectively on various systems, even with limited resources.
- **Widely Used & Supported:** Large community and plenty of available resources.
## SNORT vs IDS vs IPS
- **IDS:** Intrusion Detection System. Focuses on identifying suspicious activity but doesn’t necessarily block it.
- **IPS:** Intrusion Prevention System. Actively blocks identified threats based on predefined rules.
- **Snort:** Can function as both an IDS and an IPS, depending on your configuration.

Overall, Snort is a versatile tool that can significantly enhance your network security posture. With its powerful capabilities and flexible deployment options, it’s a valuable asset for organizations of all sizes.

# Setting up a Lab

## Important Note : If any problem occur while installation search it on YouTube rather than Google.
### Steps before installation
- open terminal and run some commands
```bash
sudo apt update
```
<img width="1121" height="351" alt="Screenshot 2026-10-01 203818" src="https://github.com/user-attachments/assets/b296e853-26fc-4383-8c12-c14b4448b032" />


```bash
sudo apt upgrade
```
<img width="1561" height="361" alt="Screenshot 2026-10-02 211751" src="https://github.com/user-attachments/assets/b6902041-5743-43b2-813d-d9732acf134c" />

## Installation on snort on Ubuntu Linux
- ## Open command terminal
- ## Paste the command
````bash
sudo apt install snort -y
````
<img width="1547" height="227" alt="Screenshot 2026-10-02 212938" src="https://github.com/user-attachments/assets/505a69e8-42f4-4a80-a09c-fa832e0f0b03" />

- Check snort is install or not by checking version

````bash
snort -v
````
<img width="1201" height="286" alt="Screenshot 2026-10-02 213634" src="https://github.com/user-attachments/assets/51c411b7-ffad-47f1-b361-e00448173f21" />

- ## check for your ifconfig
````bash
ifconfig
````
- For me it is eno1 and ip address is 192.168.51.128
<img width="1097" height="342" alt="Screenshot 2026-10-02 214808" src="https://github.com/user-attachments/assets/4c1df4ec-ed41-4d53-a3d4-289ca964cc76" />
