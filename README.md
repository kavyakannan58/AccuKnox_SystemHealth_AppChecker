# AccuKnox_SystemHealth_AppChecker
  Python project with two automation scripts: one monitors CPU, memory, and disk usage, while the other checks application uptime using HTTP status codes. Provides real-time system insights, logs performance data, and alerts when thresholds are exceeded or services are unavailable.

 # System Health Monitor & Application Health Checker
📘 Overview

This project contains two Python automation scripts that help monitor system performance and check application uptime.

System Health Monitor: Tracks CPU, memory, and disk usage with alerts for threshold breaches.

Application Health Checker: Verifies web application status via HTTP response codes and reports uptime.

⚙️ Project Structure
├── system_health_monitor.py
├── app_health_checker.py
├── requirements.txt
└── README.md

🧩 Prerequisites

Make sure you have:

Python 3.8+ installed

pip package manager

Install dependencies using:

pip install -r requirements.txt

🚀 How to Run
1️⃣ Run System Health Monitor
python system_health_monitor.py


This will check CPU, memory, and disk usage and log alerts to the console or a file.

2️⃣ Run Application Health Checker
python app_health_checker.py


It will verify application uptime using HTTP status codes and display results in the terminal.

🧠 Features

Monitors system CPU, memory, and disk usage in real time

Logs alerts for exceeded thresholds

Checks if websites or applications are online (status 200 = UP)

Simple and customizable Python implementation

🧾 Example Output
CPU Usage: 72%
Memory Usage: 63%
Disk Space: 81% - Warning: Disk usage exceeds threshold!
Website: https://example.com is UP (Status: 200)

🛠️ Tools & Technologies

Python 3

psutil

requests

**🧑‍💻 Author

Developed by Dhanalakshmi K
**
