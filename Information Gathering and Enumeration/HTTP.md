# HTTP
- Nmap scripts
```
nmap -Pn -sV -p80 --script=http-enum <ip>
```

- Directories
  - Gobuster
  ```
  gobuster dir -u http://<ip> -w /usr/share/dirb/wordlists/common.txt
  ```

  - Dirb
