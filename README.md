# -Honeypot-Attack-map-Microsoft-Azure-
This project demonstrates a Honeypot Attack Map, hosted on Microsoft Azure, designed to monitor and visualize global attack activity in real-time. The map captures and displays data from a honeypot configured to detect Remote Desktop Protocol (RDP) brute-force attacks, providing valuable insights into potential cybersecurity threats.

Features
* Attack Detection: Monitors RDP brute-force attempts using a custom PowerShell script to extract relevant metadata from Windows Event Viewer.
* Geolocation Tracking: The extracted data is forwarded to a third-party API to obtain geolocation information, pinpointing the origin of detected attacks.
* Visual Representation: Leveraging Microsoft Sentinel, the project displays attack data on a dynamic world map, showcasing attack frequency and geographic distribution.
* High-Volume Data Collection: Recorded over 9,500 attack attempts from 7 distinct locations within the first 12 hours of deployment.


Objective  
The purpose of this project is to enhance threat detection capabilities by leveraging honeypot technology and cloud-based visualization tools. The setup provides a comprehensive view of global cyber threats, allowing for a better understanding of attack patterns and potential vulnerabilities.

CREDIT: https://www.youtube.com/watch?v=RoZeVbbZ0o0&t=302s 
