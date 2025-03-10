[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=18567404)
# The Amazing Trace

### Overview
This project executes a traceroute command to a specified destination, parses the output, and structures the results for analysis. It helps in understanding network routes, and latency.

### Features
- Runs a traceroute command to a given hostname or IP address.

- Parses the output to extract hop numbers, IP addresses, hostnames, and round-trip times (RTT).

- Handles timeouts and missing data.

- Logs errors and debugging information in a log file (`amazing_trace.log`).

### Requirements
- Python
- Linux (require `traceroute` to be installed)

### Usage
- Set up a venv
- Install `matplotlib`, `pandas`, and `pytest` if not installed already
- Run the `amazing_trace.py` 
- Use: `python amazing_trace.py`
