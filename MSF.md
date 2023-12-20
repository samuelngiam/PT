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

- Workspaces
```
workspace -h
workspace
workspace -l
workspace -a <name>
workspace default
```

- Others
```
help

show all
show exploits

search -h

use <module_name> (or 'use <module_no>')
info
options (or 'show options')
set <parameter> <value> (or 'setg')
exploit (or 'run')
back

sessions
sessions -i <session_id> (or 'sessions <session_id>')
sessions -k <session_id>

connect

Ctrl + L
```
