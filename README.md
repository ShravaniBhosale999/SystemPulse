# SystemPulse – Automated System Monitoring & Log Generator

Developed a system monitoring tool that tracks CPU, memory, and disk usage and automatically generates logs for system performance analysis. This project demonstrates concepts used in cloud infrastructure monitoring and system administration.

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
