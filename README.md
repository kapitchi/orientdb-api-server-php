OrientDB RESTful JSON API server for PHP
========================================

This is concept documentation for OrientDB RESTful JSON API server for PHP.

Status: DRAFT


OAuth authentication
--------------------

Implementation of OAuth2 server with 2 and 3-legged authorization.

https://github.com/bshaffer/oauth2-server-php


_Connection to OrientDB is made on behalf of OAuth authenticated user so standard OrientDB security features (e.g. record level security) can be used._

TODO


Exposed OrientDB APIs
---------------------

/batch
------

__POST__

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#batch


/document[/:rid[/:fetchPlan]
--------------------------------

__GET - /document/:rid[/:fetchPlan]__

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#get---document

__POST - /document__

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#post---document

__PUT - /document/:rid[?updateModel=full|partial]__

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#put---document

__DELETE - /document/:rid__

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#delete---document

/sql/:queryText[/:fetchPlan]
-------------------------------

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#get---query

/function/:name[/:argument*]
------------------------------

http://www.orientechnologies.com/docs/last/orientdb.wiki/OrientDB-REST.html#post-and-get---function

