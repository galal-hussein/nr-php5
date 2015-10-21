newrelic-php5
=========

This role will install and configure  Newrelic agent for php5 on Debian or RHEL Linux based systems.

Role Variables
--------------

The following two variables are required to specify the destination of the php5 modules, and the php server used on your system (php5-fpm, apache2, etc.):

**php_modules_dest:** default to /etc/php5/mods-available

**php_server:** default to php5-fpm

The rest of variables are for newrelic.ini configuration, the variables are defined identically as the [documentation](https://docs.newrelic.com/docs/agents/php-agent/configuration/php-agent-configuration).

License
-------

MIT
