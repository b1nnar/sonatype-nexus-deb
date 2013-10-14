Sonatype Nexus OSS - Debian Packager
====================================================

Generates a debian package for installing Sonatype Nexus OSS web application with Apache Tomcat 7 servlet container.

##Build and Install###

Build using Apache Maven >= 3
~~~
$ mvn clean install
~~~

Install generated debian package using dpkg tool:
~~~
$ sudo dpkg -i target/sonatype-nexus-deb_VERSION.deb 
~~~

After installation, you can access the web application at:
~~~
 http://hostname:8080/nexus
~~~
using default username admin and password admin123.
