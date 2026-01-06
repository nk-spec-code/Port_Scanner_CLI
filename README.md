# Port Scanner

A  multithreaded TCP port scanner written in Python for identifying open ports on a target host. Designed for efficiency, flexibility, and cross-platform use.

## Problem
Sequential port scanning is slow and inefficient, especially when scanning large port ranges or unreliable networks.

## Solution
This tool scans ports concurrently using multithreading, supports flexible port input formats, applies timeouts for reliability, and outputs a clear summary of open ports.

## Features
- Scan single ports, ranges, or lists (e.g. '22', '20-100', '22,80,443,8000-8100')
- Multithreaded scanning for improved speed
- Timeout handling for slow or unstable networks
- Summary of open ports
- Cross-platform support (Windows, macOS, Linux)

## Requirements
- Python 3.xx

## Usage
Run from the terminal:

bash
python scanner.py --host <target> --ports <ports>

## Disclaimer
This tool is intended for educational purposes only. Do not scan systems you do not own or have explicit permission to test.
