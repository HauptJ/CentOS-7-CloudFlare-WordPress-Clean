RHEL 7 NGINX Wordpress with CloudFlare
======================================

[![Build Status](https://travis-ci.org/HauptJ/CloudPress.svg?branch=master)](https://travis-ci.org/HauptJ/CloudPress)

Installs and configures Firewalld, Fail2ban, Nginx, MariaDB, PHP, Redis, and the latest version of Wordpress.

Configuration file: ```group_vars/all```

Playbooks
---------

**dns.yml**: Sets up DNS records using CloudFlare API

**site.yml**: Installs and configures Wordpress
