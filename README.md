# G4HSK

From [WordPress.com's documentation on Subdomains](http://en.support.wordpress.com/domains/map-subdomain/):

> WordPress.com automatically removes the “www” from all URLs. Mapping the “www” subdomain is not supported.

This is a problem when we'd like [http://www.g4hsk.co.uk/](http://www.g4hsk.co.uk/) to stay working!

So this Heroku app should be on the other end of www. and issue compatibility redirects to the WordPress site now at [http://radio.g4hsk.co.uk/](http://radio.g4hsk.co.uk/).
