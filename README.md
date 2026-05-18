# Linux System Health Monitor

A Bash-based Linux monitoring tool designed to simulate basic system administration and help desk troubleshooting tasks. This project monitors system health metrics such as CPU usage, memory usage, disk utilization, uptime, and network connectivity directly from the Linux terminal.

## Features

- Monitors CPU utilization
- Displays memory usage statistics
- Checks disk space usage
- Tests internet/network connectivity
- Displays system uptime and load averages
- Generates warning alerts for high resource usage
- Supports log file output for troubleshooting and analysis

## Technologies Used

- Bash Scripting
- Linux Terminal
- Ubuntu/Linux Commands

## Commands & Utilities Used

- `top`
- `free`
- `df`
- `uptime`
- `ping`
- `awk`
- `grep`
- `sed`
- `bc`

## Project Goals

This project was created to strengthen:
- Linux administration skills
- Bash scripting fundamentals
- System monitoring concepts
- Troubleshooting workflows
- Automation and logging practices

## Example Script Output

```bash
===============================
 SYSTEM HEALTH MONITOR
===============================
Date: Sun May 10 10:49:43 AM EDT 2026

System Uptime:
 10:49:43 up 16:22,  0 user,  load average: 0.00, 0.02, 0.52

CPU Usage: 20%

Memory Usage:
               total        used        free      shared  buff/cache   available
Mem:           2.7Gi        73Mi       1.9Gi       156Ki       709Mi       2.6Gi

Disk Usage: 46%

Network Connectivity Test:
PING google.com (142.250.72.14)

===============================
 HEALTH CHECK COMPLETE
===============================
```

## How to Run the Script

Clone the repository:

```bash
git clone https://github.com/Lordchevy/linux-system-monitor.git
```

Navigate into the project directory:

```bash
cd linux-system-monitor
```

Make the script executable:

```bash
chmod +x monitor.sh
```

Run the script:

```bash
./monitor.sh
```

## Logging Output

To save monitoring results into a log file:

```bash
./monitor.sh >> healthlog.txt
```

View logs:

```bash
cat healthlog.txt
```

## Future Improvements

- Email alert notifications
- Colored terminal output
- Failed login monitoring
- Service and process monitoring
- Scheduled automation using cron jobs
- Port and network monitoring
- Export logs to CSV format

## Author

Damian Chevalier

## Related Skills

- Linux Administration
- Help Desk Troubleshooting
- System Monitoring
- Bash Scripting
- Cybersecurity Fundamentals
- SOC Analyst Foundations
