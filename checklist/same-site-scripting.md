# Same site scripting

Pretty lame bug. When a DNS record is pointing to a internal IP this could lead to an internal IP address such as 127.0.0.1 or 192.168.1.1 this could lead to "same site scripting".

This basically means that if the victim has a vulnerable router with a cross site scripting vulnerability or an attacker sets up an internal web server that the DNS record is pointing to victim could be attacked.

## How to resolve
Don't point DNS records to internal IP addresses (RFC 1918).
