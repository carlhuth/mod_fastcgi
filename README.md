# mod_fastcgi

Fork **with minor modifications** of official mod_fastcgi (http://www.fastcgi.com/dist/mod_fastcgi-current.tar.gz).

Author of this repository is not related to Open Market, Inc in any way.

For information on mod_fastcgi license, authors and copyright holders see file LICENSE.

## Additional features of this fork

* `-fixPaths` option for `FastCgiExternalServer` to allow URLs like 
`http://example.com/path/to/scriptfile.ext/argument1/argument2` with 
some external FastCGI servers (e.g. PHP-FPM in some configurations).

# Original README for mod_fastcgi

mod_fastcgi is a module for the Apache web server, that enables
FastCGI - a standards based protocol for communicating with
applications that generate dynamic content for web pages.

FastCGI provides a superset of CGI functionality, but a subset of the
functionality of programming for a particular web server API.
Nonetheless, the feature set is rich enough for programming virtually
any type of web application, but the result is generally more
scalable.  For more information on FastCGI, see

   http://www.fastcgi.com/

For information on installing mod_fastcgi with Apache 1.3.x, see the
file INSTALL.

For information on installing mod_fastcgi with Apache 2.x, see the
file INSTALL.AP2.

For information on configuring an installed instance of mod_fastcgi,
see the file mod_fastcgi.html in the docs/ directory, also available
online at:
 
   http://www.fastcgi.com/mod_fastcgi/docs/mod_fastcgi.html

For information on programming FastCGI applications, see:

   http://www.fastcgi.com/#Docs

Finally, if you get stuck - start with the Frequently Asked Questions
(FAQ) file at:

   http://www.fastcgi.com/docs/faq.html

If you still can't find an answer, join the developer's mailing list
at:

   http://fastcgi.com/fastcgi-developers
 