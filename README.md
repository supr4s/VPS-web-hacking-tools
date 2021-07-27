# VPS-web-hacking-tools

Automatically install some web hacking/bug bounty tools for your VPS.

O.S supported : 

- Ubuntu 20.04 x64
- Debian 10 x64
- Linux Mint 20.2 x64


[![asciicast](https://asciinema.org/a/ZjvDJJ6ZJsQvk4tuUbplaTf8a.svg)](https://asciinema.org/a/ZjvDJJ6ZJsQvk4tuUbplaTf8a)



## Installation 

```
apt-get update -y && apt-get install git -y
cd /tmp && git clone https://github.com/supr4s/VPS-web-hacking-tools && cd VPS-web-hacking-tools && ./installer.sh
```

## Available tools list

### Subdomains enumeration

- [Amass](https://github.com/OWASP/Amass)
- [Assetfinder](https://github.com/tomnomnom/assetfinder)
- [Crobat](https://github.com/Cgboal/SonarSearch)
- [Findomain](https://github.com/Findomain/Findomain)
- [Github-subdomains](https://github.com/gwen001/github-subdomains)

### DNS resolver

- [dnsx](https://github.com/projectdiscovery/dnsx)
- [MassDNS](https://github.com/blechschmidt/massdns)
- [PureDNS](https://github.com/d3mondev/puredns)

### Visual recon

- [Aquatone](https://github.com/michenriksen/aquatone)
- [Gowitness](https://github.com/sensepost/gowitness)

### HTTP probe

- [httprobe](https://github.com/tomnomnom/httprobe)
- [httpx](https://github.com/projectdiscovery/httpx)

### Web crawler

- [Gospider](https://github.com/jaeles-project/gospider)
- [Hakrawler](https://github.com/hakluke/hakrawler)

### Network scanner

- [Masscan](https://github.com/robertdavidgraham/masscan)
- [Naabu](https://github.com/projectdiscovery/naabu)
- [Nmap](https://nmap.org/)

### HTTP parameter

- [Arjun](https://github.com/s0md3v/Arjun)

### Fuzzing tools

- [ffuf](https://github.com/ffuf/ffuf)
- [Gobuster](https://github.com/OJ/gobuster)

### SSRF tools

- [SSRFmap](https://github.com/swisskyrepo/SSRFmap) *
- [Gopherus](https://github.com/tarunkant/Gopherus) *
- [Interactsh](https://github.com/projectdiscovery/interactsh) *

### API hacking tools

- [Kiterunner + API routes](https://github.com/assetnote/kiterunner) *

### Wordlists

- [SecLists](https://github.com/danielmiessler/SecLists)

### Vulns - XSS

- [Dalfox](https://github.com/hahwul/dalfox)
- [kxss](https://github.com/tomnomnom/hacks/tree/master/kxss)
- [XSStrike](https://github.com/s0md3v/XSStrike)

### Vulns - SQL Injection

- [NoSQLMap](https://github.com/codingo/NoSQLMap)
- [SQLMap](https://github.com/sqlmapproject/sqlmap)

### CMS Scanner

- [WPscan](https://github.com/wpscanteam/wpscan) *
- [droopescan](https://github.com/droope/droopescan) *
- [AEM-Hacker](https://github.com/0ang3el/aem-hacker) *

### Vulns - Scanner

- [Jaeles](https://github.com/jaeles-project/jaeles)
- [Nuclei](https://github.com/projectdiscovery/nuclei)

### JavaScript hunting

- [LinkFinder](https://github.com/GerbenJavado/LinkFinder)
- [SecretFinder](https://github.com/m4ll0k/SecretFinder)
- [subjs](https://github.com/lc/subjs)

### Useful tools

- [anti-burl](https://github.com/tomnomnom/hacks/tree/master/anti-burl)
- [getallurls](https://github.com/lc/hacks/tree/master/getallurls)
- [gron](https://github.com/tomnomnom/gron)
- [anti-burl](https://github.com/tomnomnom/hacks/tree/master/anti-burl) *
- [unfurl](https://github.com/tomnomnom/unfurl) *
- [anew](https://github.com/tomnomnom/anew) *
- [qsreplace](https://github.com/tomnomnom/qsreplace) *
- [Interlace](https://github.com/codingo/Interlace)
- [Tmux](https://github.com/tmux/tmux)
- [Ripgrep](https://github.com/BurntSushi/ripgrep)

### Note

- Refer to the usage of the tools as most of them require configuration (especially for subdomains enumeration).
- Please be careful with these tools and only use them on targets you have explicitly authorized.

**N.B** : * = added in the last update
