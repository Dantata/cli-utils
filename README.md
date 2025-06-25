# dns
A lightweight Bash script for quick DNS lookups from the command line. It strips common URL prefixes (http://, https://, www.) and fetches NS, A, MX, TXT, and DKIM records using dig.
Note: The tool checks for dkim._domainkey.$domain DKIM record - the actual DKIM may be at another subdomain.
# abuseipdb
Simple wrapper of the abuseipdb.com API to check the status of an IP address.
