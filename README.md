rule_maintenance_war
====================

Web Archive file containing all required files to run the the Business Rule Maintenance tool (e.g. using Tomcat)

Compiled with Jave 1.6 and optimized for Apache Tomcat 7.

You will need to setup the MySQL or MariaDb database before running the web application. There is an sql schema file available on Github. Import the schema into your existing MySQL server.

When the webapp is run initially, a dialog allows to define the configuration details of the database connection and the LDAP settings. This dialog can also be accessed at any time later.

There is basic LDAP support available: when a user logs in, the userid and password can be checked against the LDAP server.

Reference fields for a project may be defined. As a consequence the user does not need to type in field names and types - when writing rules or actions - but is able to select the fields from a dropdown. Reference fields are also
used as a help and documentation for the user when writing rules and actions and support the testing of the rulegroups.


    Copyright (C) 2008-2017  Uwe Geercken

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

last update: uwe geercken - 2017-06-05
