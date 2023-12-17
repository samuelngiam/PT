# RDP
- Check for RDP at non-standard port
```
msfconsole

use auxiliary/scanner/rdp/rdp_scanner
set RHOSTS <ip>
set RPORT <port>
exploit
```
