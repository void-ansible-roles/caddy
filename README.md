caddy
=====


What is does this role do?
--------------------------

This role installs and manages the caddy webserver on Void Linux.  It
can accept site definitions that use the `base-site` format.

Meta
----

Files Managed:
  * /etc/iptables.d/caddy.rules
  * /etc/caddy/Caddyfile
  * /srv/www/
  * /etc/sv/caddy/run
  * /var/service/caddy

Defaults Provided:
  * None

Variables Required:
  * caddy.tls_hostmaster: email to send notifications to for ACME issues

Optional Variables:
  * None

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [network](https://github.com/void-ansible-roles/network)
