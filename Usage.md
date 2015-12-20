# Usage #

sslaudit.pl _host_ _port_

# Example output #

**$ sslaudit.pl www.google.com**
<pre>
Connecting to www.google.com:443 - OK<br>
Certificate CN: www.google.com == Hostname: www.google.com<br>
Subject Name: /C=US/ST=California/L=Mountain View/O=Google Inc/CN=www.google.com<br>
Issuer  Name: /C=ZA/O=Thawte Consulting (Pty) Ltd./CN=Thawte SGC CA<br>
<br>
-----BEGIN CERTIFICATE-----<br>
MIIDITCCAoqgAwIBAgIQL9+89q6RUm0PmqPfQDQ+mjANBgkqhkiG9w0BAQUFADBM<br>
MQswCQYDVQQGEwJaQTElMCMGA1UEChMcVGhhd3RlIENvbnN1bHRpbmcgKFB0eSkg<br>
THRkLjEWMBQGA1UEAxMNVGhhd3RlIFNHQyBDQTAeFw0wOTEyMTgwMDAwMDBaFw0x<br>
MTEyMTgyMzU5NTlaMGgxCzAJBgNVBAYTAlVTMRMwEQYDVQQIEwpDYWxpZm9ybmlh<br>
MRYwFAYDVQQHFA1Nb3VudGFpbiBWaWV3MRMwEQYDVQQKFApHb29nbGUgSW5jMRcw<br>
FQYDVQQDFA53d3cuZ29vZ2xlLmNvbTCBnzANBgkqhkiG9w0BAQEFAAOBjQAwgYkC<br>
gYEA6PmGD5D6htffvXImttdEAoN4c9kCKO+IRTn7EOh8rqk41XXGOOsKFQebg+jN<br>
gtXj9xVoRaELGYW84u+E593y17iYwqG7tcFR39SDAqc9BkJb4SLD3muFXxzW2k6L<br>
05vuuWciKh0R73mkszeK9P4Y/bz5RiNQl/Os/CRGK1w7t0UCAwEAAaOB5zCB5DAM<br>
BgNVHRMBAf8EAjAAMDYGA1UdHwQvMC0wK6ApoCeGJWh0dHA6Ly9jcmwudGhhd3Rl<br>
LmNvbS9UaGF3dGVTR0NDQS5jcmwwKAYDVR0lBCEwHwYIKwYBBQUHAwEGCCsGAQUF<br>
BwMCBglghkgBhvhCBAEwcgYIKwYBBQUHAQEEZjBkMCIGCCsGAQUFBzABhhZodHRw<br>
Oi8vb2NzcC50aGF3dGUuY29tMD4GCCsGAQUFBzAChjJodHRwOi8vd3d3LnRoYXd0<br>
ZS5jb20vcmVwb3NpdG9yeS9UaGF3dGVfU0dDX0NBLmNydDANBgkqhkiG9w0BAQUF<br>
AAOBgQCfQ89bxFApsb/isJr/aiEdLRLDLE5a+RLizrmCUi3nHX4adpaQedEkUjh5<br>
u2ONgJd8IyAPkU0Wueru9G2Jysa9zCRo1kNbzipYvzwY4OA8Ys+WAi0oR1A04Se6<br>
z5nRUP8pJcA2NhUzUnC+MY+f6H/nEQyNv4SgQhqAibAxWEEHXw==<br>
-----END CERTIFICATE-----<br>
<br>
Valid from: Dec 18 00:00:00 2009 GMT<br>
Valid to:   Dec 18 23:59:59 2011 GMT<br>
Certificate date valid<br>
<br>
<br>
SSLv2 - DEFAULT - unsuccessfull<br>
SSLv2 - RC4-MD5 - unsuccessfull<br>
SSLv2 - EXP-RC4-MD5 - unsuccessfull<br>
SSLv2 - RC2-MD5 - unsuccessfull<br>
SSLv2 - EXP-RC2-MD5 - unsuccessfull<br>
SSLv2 - IDEA-CBC-MD5 - unsuccessfull<br>
SSLv2 - DES-CBC-MD5 - unsuccessfull<br>
SSLv2 - DES-CBC3-MD5 - unsuccessfull<br>
<br>
<br>
SSLv2 not supported by server<br>
<br>
<br>
SSLv3 - DEFAULT - successfull - 80<br>
SSLv3 - NULL-MD5 - unsuccessfull<br>
SSLv3 - NULL-SHA - unsuccessfull<br>
SSLv3 - EXP-RC4-MD5 - unsuccessfull<br>
SSLv3 - RC4-MD5 - successfull - 80<br>
SSLv3 - RC4-SHA - successfull - 80<br>
SSLv3 - EXP-RC2-CBC-MD5 - unsuccessfull<br>
SSLv3 - IDEA-CBC-SHA - unsuccessfull<br>
SSLv3 - EXP-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - DES-CBC-SHA - unsuccessfull<br>
SSLv3 - DES-CBC3-SHA - successfull - 80<br>
SSLv3 - EXP-EDH-DSS-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - EDH-DSS-CBC-SHA - unsuccessfull<br>
SSLv3 - EDH-DSS-DES-CBC3-SHA - unsuccessfull<br>
SSLv3 - EXP-EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - EDH-RSA-DES-CBC3-SHA - unsuccessfull<br>
SSLv3 - EXP-ADH-RC4-MD5 - unsuccessfull<br>
SSLv3 - ADH-RC4-MD5 - unsuccessfull<br>
SSLv3 - EXP-ADH-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - ADH-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - ADH-DES-CBC3-SHA - unsuccessfull<br>
SSLv3 - EXP1024-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - EXP1024-RC4-SHA - unsuccessfull<br>
SSLv3 - EXP1024-DHE-DSS-DES-CBC-SHA - unsuccessfull<br>
SSLv3 - EXP1024-DHE-DSS-RC4-SHA - unsuccessfull<br>
SSLv3 - DHE-DSS-RC4-SHA - unsuccessfull<br>
<br>
<br>
SSLv3 cipher score: 80 (A)<br>
<br>
<br>
TLSv1 - DEFAULT - successfull - 90<br>
TLSv1 - NULL-MD5 - unsuccessfull<br>
TLSv1 - NULL-SHA - unsuccessfull<br>
TLSv1 - EXP-RC4-MD5 - unsuccessfull<br>
TLSv1 - RC4-MD5 - successfull - 80<br>
TLSv1 - RC4-SHA - successfull - 80<br>
TLSv1 - EXP-RC2-CBC-MD5 - unsuccessfull<br>
TLSv1 - IDEA-CBC-SHA - unsuccessfull<br>
TLSv1 - EXP-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - DES-CBC-SHA - unsuccessfull<br>
TLSv1 - DES-CBC3-SHA - successfull - 80<br>
TLSv1 - EXP-EDH-DSS-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - EDH-DSS-CBC-SHA - unsuccessfull<br>
TLSv1 - EDH-DSS-DES-CBC3-SHA - unsuccessfull<br>
TLSv1 - EXP-EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - EDH-RSA-DES-CBC3-SHA - unsuccessfull<br>
TLSv1 - EXP-ADH-RC4-MD5 - unsuccessfull<br>
TLSv1 - ADH-RC4-MD5 - unsuccessfull<br>
TLSv1 - EXP-ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv1 - ADH-DES-CBC3-SHA - unsuccessfull<br>
TLSv1 - AES128-SHA - successfull - 80<br>
TLSv1 - AES256-SHA - successfull - 100<br>
TLSv1 - DHE-DSS-AES128-SHA - unsuccessfull<br>
TLSv1 - DHE-DSS-AES256-SHA - unsuccessfull<br>
TLSv1 - DHE-RSA-AES128-SHA - unsuccessfull<br>
TLSv1 - DHE-RSA-AES256-SHA - unsuccessfull<br>
TLSv1 - ADH-AES128-SHA - unsuccessfull<br>
TLSv1 - ADH-AES256-SHA - unsuccessfull<br>
TLSv1 - CAMELLIA128-SHA - unsuccessfull<br>
TLSv1 - CAMELLIA256-SHA - unsuccessfull<br>
TLSv1 - DHE-DSS-CAMELLIA128-SHA - unsuccessfull<br>
TLSv1 - DHE-DSS-CAMELLIA256-SHA - unsuccessfull<br>
TLSv1 - DHE-RSA-CAMELLIA128-SHA - unsuccessfull<br>
TLSv1 - DHE-RSA-CAMELLIA256-SHA - unsuccessfull<br>
TLSv1 - ADH-CAMELLIA128-SHA - unsuccessfull<br>
TLSv1 - ADH-CAMELLIA256-SHA - unsuccessfull<br>
TLSv1 - ADH-SEED-SHA - unsuccessfull<br>
<br>
<br>
TLSv1 cipher score: 90 (A)<br>
<br>
<br>
TLSv11 - DEFAULT - successfull - 95<br>
TLSv11 - NULL-MD5 - unsuccessfull<br>
TLSv11 - NULL-SHA - unsuccessfull<br>
TLSv11 - EXP-RC4-MD5 - unsuccessfull<br>
TLSv11 - RC4-MD5 - successfull - 80<br>
TLSv11 - RC4-SHA - successfull - 80<br>
TLSv11 - EXP-RC2-CBC-MD5 - unsuccessfull<br>
TLSv11 - IDEA-CBC-SHA - unsuccessfull<br>
TLSv11 - EXP-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - DES-CBC-SHA - unsuccessfull<br>
TLSv11 - DES-CBC3-SHA - successfull - 80<br>
TLSv11 - EXP-EDH-DSS-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - EDH-DSS-CBC-SHA - unsuccessfull<br>
TLSv11 - EDH-DSS-DES-CBC3-SHA - unsuccessfull<br>
TLSv11 - EXP-EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - EDH-RSA-DES-CBC3-SHA - unsuccessfull<br>
TLSv11 - EXP-ADH-RC4-MD5 - unsuccessfull<br>
TLSv11 - ADH-RC4-MD5 - unsuccessfull<br>
TLSv11 - EXP-ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv11 - ADH-DES-CBC3-SHA - unsuccessfull<br>
TLSv11 - AES128-SHA - successfull - 80<br>
TLSv11 - AES256-SHA - successfull - 100<br>
TLSv11 - DHE-DSS-AES128-SHA - unsuccessfull<br>
TLSv11 - DHE-DSS-AES256-SHA - unsuccessfull<br>
TLSv11 - DHE-RSA-AES128-SHA - unsuccessfull<br>
TLSv11 - DHE-RSA-AES256-SHA - unsuccessfull<br>
TLSv11 - ADH-AES128-SHA - unsuccessfull<br>
TLSv11 - ADH-AES256-SHA - unsuccessfull<br>
TLSv11 - CAMELLIA128-SHA - unsuccessfull<br>
TLSv11 - CAMELLIA256-SHA - unsuccessfull<br>
TLSv11 - DHE-DSS-CAMELLIA128-SHA - unsuccessfull<br>
TLSv11 - DHE-DSS-CAMELLIA256-SHA - unsuccessfull<br>
TLSv11 - DHE-RSA-CAMELLIA128-SHA - unsuccessfull<br>
TLSv11 - DHE-RSA-CAMELLIA256-SHA - unsuccessfull<br>
TLSv11 - ADH-CAMELLIA128-SHA - unsuccessfull<br>
TLSv11 - ADH-CAMELLIA256-SHA - unsuccessfull<br>
TLSv11 - ADH-SEED-SHA - unsuccessfull<br>
<br>
<br>
TLSv11 cipher score: 90 (A)<br>
<br>
<br>
TLSv12 - DEFAULT - successfull - 100<br>
TLSv12 - NULL-MD5 - unsuccessfull<br>
TLSv12 - NULL-SHA - unsuccessfull<br>
TLSv12 - EXP-RC4-MD5 - unsuccessfull<br>
TLSv12 - RC4-MD5 - successfull - 80<br>
TLSv12 - RC4-SHA - successfull - 80<br>
TLSv12 - EXP-RC2-CBC-MD5 - unsuccessfull<br>
TLSv12 - IDEA-CBC-SHA - unsuccessfull<br>
TLSv12 - EXP-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - DES-CBC-SHA - unsuccessfull<br>
TLSv12 - DES-CBC3-SHA - successfull - 80<br>
TLSv12 - EXP-EDH-DSS-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - EDH-DSS-CBC-SHA - unsuccessfull<br>
TLSv12 - EDH-DSS-DES-CBC3-SHA - unsuccessfull<br>
TLSv12 - EXP-EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - EDH-RSA-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - EDH-RSA-DES-CBC3-SHA - unsuccessfull<br>
TLSv12 - EXP-ADH-RC4-MD5 - unsuccessfull<br>
TLSv12 - ADH-RC4-MD5 - unsuccessfull<br>
TLSv12 - EXP-ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - ADH-DES-CBC-SHA - unsuccessfull<br>
TLSv12 - ADH-DES-CBC3-SHA - unsuccessfull<br>
TLSv12 - AES128-SHA - successfull - 80<br>
TLSv12 - AES256-SHA - successfull - 100<br>
TLSv12 - DHE-DSS-AES128-SHA - unsuccessfull<br>
TLSv12 - DHE-DSS-AES256-SHA - unsuccessfull<br>
TLSv12 - DHE-RSA-AES128-SHA - unsuccessfull<br>
TLSv12 - DHE-RSA-AES256-SHA - unsuccessfull<br>
TLSv12 - ADH-AES128-SHA - unsuccessfull<br>
TLSv12 - ADH-AES256-SHA - unsuccessfull<br>
TLSv12 - CAMELLIA128-SHA - unsuccessfull<br>
TLSv12 - CAMELLIA256-SHA - unsuccessfull<br>
TLSv12 - DHE-DSS-CAMELLIA128-SHA - unsuccessfull<br>
TLSv12 - DHE-DSS-CAMELLIA256-SHA - unsuccessfull<br>
TLSv12 - DHE-RSA-CAMELLIA128-SHA - unsuccessfull<br>
TLSv12 - DHE-RSA-CAMELLIA256-SHA - unsuccessfull<br>
TLSv12 - ADH-CAMELLIA128-SHA - unsuccessfull<br>
TLSv12 - ADH-CAMELLIA256-SHA - unsuccessfull<br>
TLSv12 - ADH-SEED-SHA - unsuccessfull<br>
<br>
<br>
TLSv12 cipher score: 90 (A)<br>
<br>
<br>
Protocol score: 90 (A)<br>
<br>
</pre>