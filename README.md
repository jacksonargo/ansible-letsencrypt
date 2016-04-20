# ansible-letsencrypt

* Installs letsencrypt in /opt/letsencrypt from github
* Installs cron job to automatically renew domains
* Creates configuration for each domain that uses webroot auth

####Coming

* Adds apache/nginx permit all rule for /.well-known/acme-challenge/
* Adds apache/nginx alias for /.well-known/acme-challenge/ to /var/www/letsencrypt-auth/
* Adds proxy config to varnish/nginx/apache for multi-head setups
