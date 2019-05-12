# HSLynk Linked Data Support

HSLynk Marmotta Access Layer provides support to Linked Data for HSLynk using Apache Marmotta as core.

## Install

Build the source code with maven:
```
mvn clean install
```

## Deploy

A WAR file containing Apache Marmotta is needed to deploy in a server such as Apache Tomcat. See more information for [installing](http://marmotta.apache.org/installation.html) Apache Marmotta. The WAR file can be found in `hmis-marmotta`. Marmotta needs a `$MARMOTTA_HOME` in order to store configuration files. By default, the home is set in the `web.xml`, but if the environmental variable is set, it will be overriding.
