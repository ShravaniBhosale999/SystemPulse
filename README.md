# SystemPulse – Automated System Monitoring & Log Generator

SystemPulse is a Python-based automated system monitoring tool that periodically captures system resource usage and running process information and stores it in structured log files for analysis.

## Features
- Monitors CPU usage
- Tracks RAM utilization
- Reports disk usage
- Captures network usage
- Logs running process details (PID, CPU %, memory %, status)
- Supports automated periodic execution using a scheduler
- Command-line interface for flexible execution

## Technologies Used
- Python
- psutil
- schedule

## How to Run

Install dependencies:
python -m pip install -r Requirements.txt

Run the project:
python SystemPulse.py 5 SystemPulseLogs

Press Ctrl + C to stop execution.

## Author
Shravani Bhosale
