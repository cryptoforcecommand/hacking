# hacking

Discovery 

NMAP Scanning
https://www.stationx.net/nmap-cheat-sheet/

NMAP Examples

nmap --help

-V verbose

-A (All - enable OS detection and versions)

example "nmap -A 192.168.1.22"

nmap --script smb-vuln-* -p445 192.168.61.40 

use mimikats for smb exploit after finding vulnerability

Web Vul Scanner
nikto -h http://192.168.1.32:5357


dirbuster:
- built in Kali Linux
- scans for directories on web host

Living Off the Land Binaries (Linux)
https://gtfobins.github.io/gtfobins/bash/

Living Off the Land Binaries (Windows)
https://lolbas-project.github.io/

Google Hacking Database
exploit-db.com/ghdb

Transfer Files Web Connection
"Host A"
python3 -m http.server 8000

"Remote A"
curl http:hostA.com 


searchsploit
example: searchsploit HP Power manager
