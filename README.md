# Lightweight-Honeypot-Lab-for-Intrusion-Monitoring-Kali-PentBox-
A lightweight honeypot lab using PentBox on Kali Linux to detect, log, and analyze intrusion attempts in a controlled environment.

📌 Overview
This project demonstrates the setup and deployment of a low-to-mid interaction honeypot using PentBox on Kali Linux.
The honeypot simulates a vulnerable web service to detect and log unauthorized access attempts.

🎯 Objectives
Deploy a honeypot on port 80
Simulate a fake web service
Capture and analyze intrusion attempts
Understand attacker behavior in a controlled environment

🛠️ Tools & Technologies
Kali Linux
PentBox (Ruby-based security toolkit)
VMware Workstation
HTTP protocol analysis

⚙️ Setup & Installation
# Clone repository
git clone https://github.com/technicaldada/pentbox

# Navigate to directory
cd pentbox

# Extract files
tar -zxvf pentbox.tar.gz

# Move into folder
cd pentbox-1.8

# Run PentBox
sudo ruby pentbox.rb

🚀 Configuration Steps
Select Network Tools
Choose Honeypot
Select Manual Configuration
Set -
Port: 80
Fake Message: "YOU HAVE BEEN BLOCKED! TRY AGAIN LATER"
Enable logging
Activate honeypot

📊 Features
Detects incoming HTTP requests
Logs attacker IP address and request details
Displays intrusion alerts in real-time
Blocks access with a fake response message

🧪 Demonstration
🔹 PentBox Setup
🔹 Honeypot Configuration
🔹 Honeypot Activation
🔹 Intrusion Detection Logs
🔹 Attacker View (Blocked Page)

🔍 Sample Log Output
INTRUSION ATTEMPT DETECTED!
IP: 192.168.1.7
Request: GET / HTTP/1.1
User-Agent: Firefox

📈 Learning Outcomes
Understanding of honeypot concepts (low vs high interaction)
Hands-on experience with intrusion detection
Network traffic monitoring basics
Exposure to attacker request patterns

⚠️ Disclaimer
This project is created for educational purposes only.
Do not deploy honeypots on public networks without proper authorization.
