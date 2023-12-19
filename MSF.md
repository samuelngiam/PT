# MSF

- Path
```
/usr/share/metasploit-framework
```

- Database
```
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

- MSFconsole
```
Ctrl + L

help

version

show all
show exploits

search 
search -h

show options (or 'options')

run (or 'exploit')

back

use <module_name> (or 'use <module_no>')

sessions

connect
```
