# MSF

## eJPT
- Installing & Configuring MSF
```
/usr/share/metasploit-framework

sudo apt-get update && sudo apt-get install metasploit-framework

sudo systemctl enable postgresql
sudo systemctl start postgresql
sudo systemctl status postgresql

sudo msfdb
sudo msfdb init
sudo msfdb reinit
sudo msfdb status

msfconsole
db_status
```

- MSFconsole Fundamentals
```
Ctrl + L

help

version

show all
show exploits

search portscan
use auxiliary/scanner/portscan/tcp

```
