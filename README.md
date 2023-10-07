# Recon Part:

## Wayback machine to view old files in Web archive
```
Web:
https://web.archive.org/cdx/search/cdx?url=*.domain.com&fl=original&collapse=urlkey

Using CURL
$ curl -v -X POST 'https://web.archive.org/cdx/search/cdx?url=*.domain.com&fl=original&collapse=urlkey' | grep "http" | tee OutputWeb.txt
```
## Use Waybackurls by tomnomnom:
```
$ waybackurls domain.com
$
```
## Use Knock Subdomain Scan:
```
$ python knockpy.py domain.com
```
## Use Subfinder for subdomain scan:
```
$ subfinder -d domain.com
```
### Use Assetfinder for subdomain scan:
```
$ assetfinder -subs-only domain.com
```
## Use Sublist3r for subdomain scan:
```
$ python sublis3r.py -d domain.com -p 80 443
```
### After complete Subfinder+Assetfinder+Sublist3r:
All the output subdomains list to compress with a one final subdomain list.
```
(Will soon...!)
```
## Find Sub-domains of Sub-doamin
***Some website have 5th and 6th level sub-domain***

#### Tool: altdns -https://github.com/infosec-au/altdns
Input : sub-domain list
```
$ python altdns.py -i Final_Output_Subdomains.txt -o output -w words.txt -r -s Final_subs_of_subs_output.txt
```
#### Tool: SubBrute
```
$ python subbrute.py domain.com > subBrute_sudomains.txt
Then
$ python subbrute.py –t subBrute_sudomains.txt
```
## dnsx
dnsx is a fast and multi-purpose DNS toolkit designed for running various probe through the retryabledns libery.
Link: https://github.com/projectdiscovery/dnsx
```
$ dnsx (will soon...!)
```
### Now We Have WaybackURls + Subdomains + Subdomains of Subdomains
## Check Subdomain Validation:
Tool: httpx
```
$ cat finalsubdomain.txt | httpx --status-code -title
```
Tool: EyeWitnes (https://github.com/RedSiege/EyeWitness)
```
$ python EyeWitness.py -f finalsubdomain.txt
```
## Google Dorks:
```
- site: “domain.com” + “domain” + password
- site:target.com filetype:php
- site:target.com filetype:aspx
- site:target.com filetype:swf (Shockwave Flash)
- site:target.com filetype:wsdl
- site: target.com inurl:.php?id=
- site: target.com inurl:.php?user=
- site: target.com inurl:.php?book=
- site: target.com inurl:login.php
- site: target.com intext: “login”
- site: target.com inurl:portal.php
- site: target.com inurl:register.php
-site: target.com intext: “index of /”
```
## Shodan:
```
(Will Soon...!)
```
## Censys:
```
(Will Soon...!)
```
## Zoomeye:
```
(Will Soon...!)
```
## Others:
```
(Will Soon...!)
```
## Directory Bruteforce:
Tool: ffuf
```
$ ffuf -u domain.com/FUZZ -w wordlist.com -mc 200,301,401 -recursion
```
Tool: Dirsearch
```
$ python dirsearch.py -u domain.com
```
Tool: Gobuster and Others
```
$ dirb
$ gobuster
$ dirbuster
```
## LinkFinder:(https://github.com/GerbenJavado/LinkFinder)
LinkFinder is a python script written to discover endpoints and their parameters in java Scripts files.
```
$ python linkfinder.py -i https://domain.com -o cli
```
## TiDos: (https://github.com/0xInfection/TIDoS-Framework)
TiDos is an offensive web application framework with lots of modules.It helps in many penetration testing task from performing recon to attacking a web application.
```
$ python tidos.py
```
Reference: https://www.youtube.com/watch?v=5a_GFWeovYI
## Photon: (https://github.com/s0md3v/Photon)
Photon is basically a data extraction tool which helps us find many useful information from the websites.
```
$ python3 photon.py -u domain.com — keys — dns
```
## References:
https://medium.com/@theUnixe/recon-for-web-pen-testing-6a6333673818

