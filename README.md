Common Lisp REST Server
=======================

*rest-server* is a library for writing REST Web APIs in Common Lisp

[![Build Status](https://travis-ci.org/mmontone/cl-rest-server.svg?branch=master)](https://travis-ci.org/mmontone/cl-rest-server)

Documentation:

[HTML](http://mmontone.github.io/cl-rest-server/doc/build/html)

[PDF](http://mmontone.github.io/cl-rest-server/doc/build/latex/CommonLispRESTServer.pdf)

Features:

* Method matching
  - Based on HTTP method (GET, PUT, POST, DELETE)
  - Based on Accept request header
  - URL parsing (argument types)

* Serialization
  - Different serialization types (JSON, XML, S-expressions)

* Error handling
  - Development and production modes
  - HTTP status codes

* Validation via schemas

* Annotations for api logging, caching, permission checking, and more.

* Authentication
  - Different methods (token based, oauth)

* API client
  - Generation of API client functions via macros

* APIs documentation
  - Via Swagger: http://swagger.wordnik.com
