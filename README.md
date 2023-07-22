
# **Port Scanner**
## Introduction
Welcome to the Port Scanner project! This simple Python script allows you to scan for open ports on one or multiple target IP addresses. The script utilizes sockets to check the connectivity of each specified port on the given targets.

## Requirements
To run this script, you need the following:
- Python 3.x
- The `socket` library, which is usually included with Python by default.

## Usage
You can run the script using the command line. Here's how you can use it:
```python
python port_scanner.py
```
The script will prompt you to enter the targets and the number of ports you want to scan.

1. Enter the targets to scan. You can enter a single target or multiple targets separated by commas, for example:

- Single target: `192.168.0.1`
- Multiple targets: `192.168.0.1, 8.8.8.8, 10.0.0.1`

2. Enter the number of ports you want to scan.
 The script will scan ports from 1 to the specified number.

## Example
Let's say you want to scan for open ports on two targets:

`192.168.0.1` and `8.8.8.8`, and scan the first 1000 ports.

You would run the script like this:
```python
python port_scanner.py
[*] Enter Targets To Scan (split them by ,): 192.168.0.1, 8.8.8.8
[*] Enter How Many Ports You Want To Scan: 1000
```
The script will then start scanning for open ports on the specified targets and display the results.

## Acknowledgments
This Port Scanner project is a simple educational tool and may have limitations. It should not be used for any malicious purposes.
Always ensure that you have proper authorization before scanning any target systems

## Disclaimer
**The Port Scanner is provided as-is without any warranty. The developers are not responsible for any misuse or damages caused by the use of this tool. Use it responsibly and at your own risk.**

Happy scanning!
