# Recon Part:

## Wayback machine to view old files in Web archive
```
https://web.archive.org/cdx/search/cdx?url=*.domain.com&fl=original&collapse=urlkey
```
## Use Waybackurls by tomnomnom:
```
$ waybackurls domain.com
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
(Will Soon...!)
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
##

##
##

## References:
https://medium.com/@theUnixe/recon-for-web-pen-testing-6a6333673818

