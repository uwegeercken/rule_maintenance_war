rule_maintenance_war
====================

Web Archive file containing all required files to run the the Business Rule Maintenance tool (using e.g. Tomcat)

Compiled with Jave 1.8 and optimized for Apache Tomcat 9.

Make sure you have a MySQL or Mariadb server running. You will need a user and user password which allows to create the database, tables and some initial data.

When the webapp is run initially, a dialog allows to define the configuration details of the database connection and the LDAP settings. This dialog can also be accessed at any time later.

There is basic LDAP support available: when a user logs in, the userid and password can be checked against the LDAP server.

Reference fields for a project may be defined. As a consequence the user does not need to type in field names and types - when writing rules or actions - but is able to select the fields from a dropdown. Reference fields are also used as a help and documentation for the user when writing rules and actions and support the testing of the rulegroups.

Please also read the documentation: https://github.com/uwegeercken/rule_maintenance_documentation/blob/master/business_rules_maintenance_web_application.pdf


    Copyright (C) 2008-2019  Uwe Geercken

 Licensed to the Apache Software Foundation (ASF) under one
 or more contributor license agreements.  See the NOTICE file
 distributed with this work for additional information
 regarding copyright ownership.  The ASF licenses this file
 to you under the Apache License, Version 2.0 (the
 "License"); you may not use this file except in compliance
 with the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing,
 software distributed under the License is distributed on an
 "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
 KIND, either express or implied.  See the License for the
 specific language governing permissions and limitations
 under the License.

last update: uwe geercken - 2019-06-10

