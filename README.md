# Detecting Unauthorized Access Attempts Using a Raspberry Pi Honeypot

## Deployed an SSH honeypot on a Raspberry Pi using Cowrie to capture and analyze unauthorized login attempts, usernames, passwords, and IP addresses.

## Materials and Tools
- Hardware: Raspberry Pi 4
- OS: Raspberry Pi OS
- Network: Wireless network
- Tooling: Cowrie SSH Honeypot
- Language/Runtime: Python virtual environment

## Implementation
- Installed Raspberry Pi OS and enabled SSH
- Configured headless access and remote terminal control
- Deployed Cowrie honeypot within a Python virtual environment
- Configured Cowrie to emulate an SSH service on port 2222

## Validation 
- Verified Cowrie service startup
- Generated test login attempts using fake credentials
- Confirmed capture of usernames, passwords, IP addresses, and timestamps

## Challenges
- Initial difficulty testing the honeypot
- Misconfiguration of authentication behavior
- Resolution through Cowrie configuration changes



