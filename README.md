run-easy
========

A template to generate an executable distribution of portable self-contained java tools such as HSQLDB, H2, etc, rely on application assembler maven plugin(http://mojo.codehaus.org/appassembler/appassembler-maven-plugin/)

To generate a executable hsqldb distribution, run
mvn package -Dapp=hsqldbsrv
you will then get dist package generated in target folder in zip, tar, tar.gz, tar.bz2 format.
