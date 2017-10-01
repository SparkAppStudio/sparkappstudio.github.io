# sparkappstudio.github.io
Spark App Studio Website Landing Page

Uses Bootstrap framework: https://getbootstrap.com/docs/4.0/getting-started/introduction/

******

# DNS
Registeed with Google.
http://domains.google.com

Since we're using Github pages, we just point our dns records to github's servers.
https://help.github.com/articles/setting-up-an-apex-domain/
https://help.github.com/articles/setting-up-a-www-subdomain/

The recommend pointing both the apex and the www subdomain, so I've set both of those up.
You can check the A record with,
`dig +noall +answer sparkappstudio.com`
You should see both of the GitHub IPv4 Addresses returned

https://help.github.com/articles/setting-up-a-www-subdomain/

We also have the `www` subdomain pointing here as well because it's recommended.
https://help.github.com/articles/about-supported-custom-domains/

`dig www.sparkappstudio.com +nostats +nocomments +nocmd`
Shows the www pointing to the bare, and pointing to the GitHub IPv4 Addresses

