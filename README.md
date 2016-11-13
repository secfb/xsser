XSSER
==========

<a href="https://www.blackhat.com/eu-15/arsenal.html"><img alt="Black Hat Arsenal" src="https://www.toolswatch.org/badges/arsenal/2015.svg" /></a>

<a href="https://www.blackhat.com/eu-16/arsenal.html"><img alt="Black Hat Arsenal" src="https://www.toolswatch.org/badges/arsenal/2016.svg" /></a>

### Presentation 
* From XSS to RCE 2.5 - Black Hat Europe Arsenal 2016

Note: The rest of this page and associated code has not been updated yet. Deployment test.

### Demo
* https://www.youtube.com/playlist?list=PLIjb28IYMQgqqqApoGRCZ_O40vP-eKsgf

Requirements
------------
* Python (2.7.*, version 2.7.3 was used for development and demo)
* Gnome
* Bash
* Msfconsole (accessible via environment variables)
* Netcat (nc)

Payload Compatibility
------------
* Firefox (Confirmed in a previous version)
* Chrome (Confirmed for the latest version - 14 Nov 2015)

WordPress Lab
------------------
* WordPress http://wordpress.org/
* Better WP Security http://www.exploit-db.com/wp-content/themes/exploit/applications/c6d6beb3c11bc58856e15218d512b851-better-wp-security.3.5.3.zip
* Optional: WPSEO https://yoast.com/wordpress/plugins/seo/

WordPress Exploit
------------------
* http://www.exploit-db.com/exploits/27290/

Directories
------------
* Payloads/javascript: Contains the JavaScript payloads
* Shells: Contains the PHP shells to inject

Developed By
------------
* Hans-Michael Varbaek
* Sense of Security

Credits
------------
* MaXe / InterN0T

Code Design
-----------
* It works!
* Spaghetti code
* Just-In-Time for Black Hat Europe 2015
