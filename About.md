# Introduction #

SSLAudit is a tool that verifies SSL certificate and supported protocols/ciphers of a SSL-enabled webserver. The result is graded according to [SSLLabs SSL Server Rating Guide](https://www.ssllabs.com/projects/rating-guide/index.html).

The tool is similar in function to  [SSLDigger from Foundstone](http://www.foundstone.com/us/resources/proddesc/ssldigger.htm) and [THCSSLCheck from The Hacker Choice](http://freeworld.thc.org/root/tools/) but is different that it is open source and is easily modified to support new protocols and ciphers as they become available and the result is graded. [SSLScan](http://sourceforge.net/projects/sslscan/) (with associate [output perl parser](http://search.cpan.org/~jabra/Sslscan-Parser-0.02/)) does many things similar to SSLAudit and can serve your purpose well, however it doesn't do the grading (which is a minor thing as the output is detailed and you have the perl module to parse the logfile) and I had problems getting it compile under Windows/Cygwin. SSLLabs has a [online service](https://www.ssllabs.com/ssldb/analyze.html) to scan public-facing SSL-servers (but can't handle internal servers or servers with restricted internet access).


This project is sponsored by [Omegapoint AB](http://www.omegapoint.se) and was created to assist security assessments done according to [OWASP Testing Guide](http://www.owasp.org/index.php/Category:OWASP_Testing_Project).

# Details #

Currently SSLAudit performs the following checks:
  * SSL Protocol support detection
  * SSL Cipher support detection
  * Public cert PEM extraction
  * Certificate timeframe validation (and warns if it is 30 days or less until the certificate expires)
  * Grading of result according to SSLLabs SSL Server Rating Guide