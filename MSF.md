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
show options (or 'options')
setg
run (or 'exploit')
back

sessions
sessions -i <session_id> (or 'sessions <session_id>')

connect

Ctrl + L
```
