rule_maintenance_war
====================

Web Archive file containing all required files to run the the Business Rule Maintenance tool (e.g. using Tomcat)

Compiled with Jave 1.7 and optimized for Apache Tomcat 7.

You will need to setup the MySQL database before running the web application. There is an sql schema file available on Github. Import the schema into your existing MySQL server.

When the webapp is run initially, a dialog allows to define the configuration details of the database connection and the LDAP settings.

There is basic LDAP support available: when a user logs in, the userid and password can be checked against the LDAP server.

A transformation from Pentaho PDI containing Rule Engine steps may be imported. As a consequence the user does not need to type in field names and types - when writing rules or actions - but may select the fields from a dropdown.

last update: uwe geercken - 2016-02-29
