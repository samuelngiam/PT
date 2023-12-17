# RDP
- Check for RDP at non-standard port
  - Nmap will not identify RDP e.g. on port 3333
```
msfconsole

use auxiliary/scanner/rdp/rdp_scanner
set RHOSTS <ip>
set RPORT <port>
exploit
```
