jMonkey Maven SDK
=================

The Maven jMonkey SDK Helper is a helper maven project that can be used to install the libraries necessary to build JME applications with Maven.

How to install
--------------

### Install thirdparty into local repository:

    $ cd jme3-maven-helper/jme3-thirdparty
    $ mvn install
    
    
### Enabled maven for jme

    $ cp jme3-maven-helper/jme3-buildhelper/pom.xml $JME_HOME/pom.xml
    
Now you can build jme3 with maven!

Use JME3 in maven project
-------------------------

```xml
  <dependency>
      <groupId>com.jme3</groupId>
      <artifactId>jMonkeyEngine3</artifactId>
      <version>3.0.0-SNAPSHOT</version>
  </dependency>
```