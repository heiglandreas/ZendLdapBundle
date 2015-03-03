Org_Heigl\LdapBundle
====================

This bundle integrates \Zend\Ldap into Symfony

Nothing more, nothing less!

Usage
-----

You can use it via ```$ldap = $this->get('ldap');```

Configuration
-------------

Configure it by adding the following keys and their appropriate vaues to your
```parameters.yml``` file:

* ldap_host: Your LDAP-Server
* ldap_username: The username to connect to the ldap for read-queries. Might be "null" for anonymous access
* ldap_password: The password of that same ldap-user. Might be "null" for anonymous access
* ldap_baseDn: The base-DN of your LDAP-server