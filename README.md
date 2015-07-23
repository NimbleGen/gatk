The Genome Analysis Toolkit
============

This repository is a fork of the GATK Official Release Repository.  Modifications to date include the addition of a 
NimbleGen module that is currently a placeholder for any custom tools built upon the GATK framework.  Compiling code 
from this repository creates an executable JAR file that contains the GATK tools and utilities that are free 
for all uses alongside any custom tools added to this repository.
  
Instructions to compile code contained in this repository are below.

###Requirements

```
Java 1.7
Apache Maven 3.0.5 or greater
```


### Compile notes

The compile procedure below is performed using Apache Maven.  Prior to compiling with maven, be sure that 
$JAVA_HOME is set properly.

For example on Ubuntu, Xubuntu, or similar this can be achieved using the following command:

```
> export JAVA_HOME=/usr/lib/jvm/java-7-oracle
```

See also:

1. <a href="http://askubuntu.com/questions/459900/how-to-find-my-current-java-home-in-ubuntu">
        Ask Ubuntu: How to find my current java home in ubuntu </a>
2. <a href="http://askubuntu.com/questions/303672/jres-from-different-vendors-on-the-same-system/458796#458796">
        Ask Ubuntu: JREs from different vendors on the same system </a>

###Compile commands

```
 > git clone https://github.com/NimbleGen/gatk.git
 > cd gatk
 > mvn verify
```

#####Download JAR

<a href="https://github.com/NimbleGen/gatk/releases/tag/3.4">GATK Version 3.4</a>


#####References:

1. http://www.broadinstitute.org/gatk/

#####Disclaimer:

Roche does not provide direct analysis support or service for these or any other third party tools. Please refer to
the authors of each tool for support and documentation.