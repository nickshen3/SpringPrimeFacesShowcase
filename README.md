Spring Web Flow Samples
=======================

These examples from official samples repository from [Spring Web Flow](http://github.com/SpringSource/spring-webflow) project.
They are updated to run under websphere environment.

Build and Run
=============

Running 'mvn clean package' from this directory generates .war files for all samples.

For example running booking mvc example:

````
cd booking-mvc
mvn tomcat7:run
````

For example running primefaces showcase example:

````
cd primefaces-showcase
mvn tomcat7:run
````

Eclipse
=======

Generate Eclipse settings for all samples:

````
mvn eclipse:clean eclipse:eclipse
````

Import the projects into Eclipse. The Eclipse preferences must have an `M2_REPO` under "Java", "Build Path", "Classpath Variables".

Contributing
============

[Pull requests](http://help.github.com/send-pull-requests) are welcome.

