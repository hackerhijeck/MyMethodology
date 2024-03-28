## My Recon
#### Target with wildcard (*domain.com)

### Passive Subdomains
```
## Crt.sh
```
https://crt.sh/?q=domain.com
curl -s https://crt.sh/\?q\=\google.com\&output\=json | jq -r '.[].name_value' | grep -Po '(\w+\.\w+\.\w+)$'
```

## Virus Total
https://www.virustotal.com

## Shodan.io
1. Ssl.cert.subject.CN:"anymeeting.com"  -http.title:"Invalid URL"  -http.title:"403 - Forbidden: Access is denied."
2. ssl:"domain.com"

## ZooomEye
site:"anymeeting.com"

## URLScan.io
https://urlscan.io/

## LeakIX:
https://leakix.net

## Greynoise.io
https://viz.greynoise.io

## Archive
1. https://web.archive.org/cdx/search/cdx?url=*.domain.com&fl=original&collapse=urlkey
2. $ curl "https://web.archive.org/cdx/search/cdx?url=*.anymeeting.com&fl=original&collapse=urlkey" | tee archive.txt
```

### Take subdomains from Crt.sh, Shodan.io, Virus Total and make a file and Remove the duplicates Subdomains:
```
$ sort -u domain_list.txt -o domain_list.txt
```
## Js file analyze amnual:
```
"/, aws, algolia, s3.
```
