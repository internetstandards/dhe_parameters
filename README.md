# Pre-defined DHE groups
This repository contains .pem files for pre-defined DHE groups as recommended by [IETF RFC 7919](https://tools.ietf.org/html/rfc7919) for: 
* `ffdhe4096`
* `ffdhe3072`
* `ffdhe2048`

## Testing with Internet.nl
With the [Internet.nl](https://internet.nl) test tool you can test if your web or mail server uses these groups for Diffie-Hellman key exchange. 

## NCSC-NL TLS Guidelines
Internet.nl uses the ['IT Security Guidelines for Transport Layer Security (TLS) version 2.0'](https://english.ncsc.nl/publications/publications/2019/juni/01/it-security-guidelines-for-transport-layer-security-tls) from NCSC-NL (in English) as a baseline. NCSC-NL gives the following security status to these groups (guideline B6-1 and table 10):

* Sufficient: `ffdhe4096` and `ffdhe3072`
* Phase out: `ffdhe2048`
