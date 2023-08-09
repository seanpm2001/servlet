# Jakarta Servlet

This repository contains the code for Jakarta Servlet.

[Online JavaDoc](https://javadoc.io/doc/jakarta.servlet/jakarta.servlet-api/)

About Jakarta Servlet
---------------------
Jakarta Servlet defines a server-side API for handling HTTP requests and responses.

Building
--------
Prerequisites:

* JDK 11+
* Maven 3.5.4+

Run the build: 

`mvn install`

The build runs copyright check and generates the jar, sources-jar and javadoc-jar by default.
The API jar is built in /api/target.

Checking findbugs
-----------------
`mvn -DskipTests -Dfindbugs.threshold=Low findbugs:findbugs`

