## My Recon
#### Target with wildcard (*domain.com)

### Passive Subdomains
```
## Crt.sh
https://crt.sh/?q=domain.com

## Virus Total
https://www.virustotal.com

## Shodan.io
1. Ssl.cert.subject.CN:"anymeeting.com"  -http.title:"Invalid URL"  -http.title:"403 - Forbidden: Access is denied."
2. ssl:"domain.com"

## Archive
1. https://web.archive.org/cdx/search/cdx?url=*.domain.com&fl=original&collapse=urlkey
2. curl "https://web.archive.org/cdx/search/cdx?url=*.anymeeting.com&fl=original&collapse=urlkey" | tee archive.txt
```

### Take subdomains from Crt.sh, Shodan.io, Virus Total and make a file and Remove the duplicates Subdomains:
```
$ sort -u domain_list.txt -o domain_list.txt
``
