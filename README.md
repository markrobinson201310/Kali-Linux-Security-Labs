Added user permissions using AD
Lab Environment
- Attacker: Kali Linux
- Target: Ubuntu VM
- Tool: Hydra
- Service: SSH (Port 22)
- Wordlist: rockyou.txt
 Log Analysis
Monitored SSH logs using:
journalctl -u ssh
Indicators of Compromise (IOCs)
- High frequency failed login attempts from a single IP
- Repeated authentication failures
- SSH session termination after threshold exceeded
