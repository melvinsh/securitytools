# tools
Diverse tools voor pentesten en netwerkscans.

```
├── general
│   ├── BurpToggle                          # Burp Suite aan/uit switch voor OS X.
│   ├── install_burp                        # Installeer Burp Suite Free.
│   └── serve                               # Lokale HTTP server.
├── lists
│   ├── SecLists                            # Hele boel lijstjes.
│   ├── directory-list-2.3-big.txt
│   ├── directory-list-2.3-medium.txt
│   ├── directory-list-2.3-small.txt
│   ├── directory-list-lowercase-2.3-big.txt
│   ├── directory-list-lowercase-2.3-medium.txt          # Aanbevolen voor HTTP bruteforce!
│   ├── directory-list-lowercase-2.3-small.txt
│   └── top-1m.csv.zip
├── local
│   ├── LinEnum                              # Scripted Local Linux Enumeration & Priv checks.
│   ├── linux-mustread                       # Artikel over Linux privilege escalation.
│   ├── lynis                                # Local scanner for Linux, Mac OS, and Unix.
│   └── PowerSploit                          # Windows PowerShell exploitation.
├── mobile
│   ├── ssl-kill-switch2                     # Stop SSL certificate pinning in iOS.
├── networks
│   ├── aws_pwn                              # Tools voor AWS hacking.
│   ├── nmap                                 # Beste poortscanner.
│   ├── subbrute                             # Bruteforce subdomais.
│   ├── sublister                            # Subdomain discovery/bruteforce.
│   ├── subresolve                           # Test output van bovenstaande tools .
│   └── testssl.sh                           # Lokale Qualys SSL labs.
├── webapps
│   ├── HTTPLeaks                            # Hoe kunnen HTTP requests lekken in HTML?
│   ├── XSS.payload.html                     # XSS payloads.
│   ├── cors_exploit.html                    # Voorbeeld van CORS exploit.
│   ├── cors_exploit2.html                   # & nog 1.
│   ├── dirsearch                            # Directory bruteforce.
│   ├── gitTools                             # Probeert open .git directory van webserver te halen.
│   ├── jexboss                              # Pwn jboss.
│   ├── jquery_pre_3_poc.html                # jQuery vulnerability.
│   ├── oxml_xxe                             # XXE tool.
│   ├── schema.svg                           # XSS in een SVG.
│   ├── ssrf_proxy                           # Tunnel HTTP door SSRF vuln site.
│   ├── uber.gif                             # DoS GIF.
│   ├── wpscan                               # Wordpress scanner.
│   └── whatweb                              # Web fingerprinting.
└── wireless
    ├── WiFi-Pumpkin                         # GUI voor Wifi attacks.
    ├── airgeddon                            # Bash script om Wifi attacks te automatiseren. 
    └── fluxion                              # MITM WPA aanvallen.
```

## Ophalen en bijdragen
Om alle submodules direct binnen te halen:
```
git clone --recursive git@github.com:InsiteSecurity/tools.git
```

Voorbeeld van submodule toevoegen:
```
git submodule add https://github.com/melvinsh/BurpToggle.git BurpToggle
git add .gitmodules BurpToggle
git commit -m "add BurpToggle"
git push
```
