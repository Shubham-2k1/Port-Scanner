# Port Scanner

## Description
This Python script is a simple port scanner designed to scan for open ports on a specified IP address. It takes an IP address as an argument and scans a range of ports to check for their status (open or closed).

## Syntax
python3 scanner.py IP_Address

## Usage
- Provide the IP address of the target machine as an argument to the script.
- The script will scan a predefined range of ports on the specified IP address and report back the status of each port.

## Example
python3 scanner.py 192.168.0.1

## Features
- The script scans a range of ports starting from a defined starting port to an ending port.
- It prints a banner indicating the target being scanned and the time the scan started.
- For each port scanned, it reports whether the port is open or closed.
- The script utilizes the `socket` module for network communication and `datetime` module to display the current time.
- It handles errors such as invalid arguments, hostname resolution failure, and connection errors gracefully.

## Note
- Ensure you have proper authorization before scanning any target.
- This script is for educational purposes and should be used responsibly.
- Modify the script's variables `Port_Range_Starting` and `Port_Range_Ending` to specify the range of ports to scan according to your requirements.
