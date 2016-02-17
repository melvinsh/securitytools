# tools
Diverse tools voor pentesten en netwerkscans.

- BurpToggle - OS X tool om Burp proxy snel aan/uit te zetten.
- dirsearch - Directory/file brute force.
- lists - Directory/file name lijsten (gesorteerd op meest voorkomend).
- subbrute - Subdomein brute force.
- wpscan - Wordpress scanner.
- XSS.payload.html - Goede XSS payloads.
- cors_exploit - HTML5 CORS policy misconfiguration exploit PoC.
- install_burp - Burp (Free) install script voor OS X.
- serve - Snel een lokale HTTP server in een directory.
- testssl.sh - Qualys-achtige SSL tester.
- top-1m.csv.zip - Top 1m passwords lijst.

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
