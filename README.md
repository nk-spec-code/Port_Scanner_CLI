
# Port Scanner

Identifying open ports on a host using basic or sequential methods was slow and inefficient, especially when scanning large port ranges or unreliable networks. Built a multithreaded TCP port scanner in Python that scans ports concurrently, supports flexible input formats, applies timeouts for reliability, and outputs a clear summary of open ports.

## Features
- Scans single ports, ranges, or lists e.g "22, 20-100," or "22,80,443,8000-8100"
- Multithreaded scanning for speed
- Timeout feature for slow networks
- Summary of open ports
- Works on Windows, MacOS, Linux 

## Usage 
Run from terminal 
- python scanner.py <host> [options]

