SSLAudit is a tool that verifies SSL certificate and supported protocols/ciphers of a SSL-enabled webserver. The result is graded according to [SSLLabs SSL Server Rating Guide](https://www.ssllabs.com/projects/rating-guide/index.html).

There are many similar tools out there, but none of them did what I needed:

  * [SSLDigger from Foundstone](http://www.foundstone.com/us/resources/proddesc/ssldigger.htm) and [THCSSLCheck from The Hacker's Choice](http://freeworld.thc.org/root/tools/) are proprietary software and are not easily maintainable. They are also quite old:
    * SSLDigger was last updated 2004, and does not work on newer releases of Windows.
    * THCSSLCheck was last updated 2006
  * [SSLScan](http://sourceforge.net/projects/sslscan/) (with associate [output perl parser](http://search.cpan.org/~jabra/Sslscan-Parser-0.02/)) does many things similar to SSLAudit and can serve your purpose well, however it doesn't do the grading (which is a minor thing as the output is detailed and you have the perl module to parse the logfile) and I had problems getting it compile under Windows/Cygwin.
  * SSLLabs has a [online service](https://www.ssllabs.com/ssldb/analyze.html) to scan public-facing SSL-servers (but can't handle internal servers or servers with restricted internet access).

SSLAudit does what I need: it is open source and is easily modified to support new protocols and ciphers as they become available, the result is graded and it runs both on Linux and Windows.

This project is sponsored by [Omegapoint AB](http://www.omegapoint.se) and was created to assist security assessments done according to [OWASP Testing Guide](http://www.owasp.org/index.php/Category:OWASP_Testing_Project).