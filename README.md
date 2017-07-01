[![Travis branch](https://img.shields.io/travis/protobufel/protobufel-maven-parent/master.svg?style=plastic)](https://travis-ci.org/protobufel/protobufel-maven-parent)
[![codecov](https://codecov.io/gh/protobufel/protobufel-maven-parent/branch/master/graph/badge.svg)](https://codecov.io/gh/protobufel/protobufel-maven-parent)
[![Maven Central](https://img.shields.io/maven-central/v/com.github.protobufel/protobufel-maven-parent.svg?style=plastic)](https://search.maven.org/#search%7Cga%7C1%7Ca%3A%)

### Protobufel Maven Parent Project 

This is a parent project for all protobufel maven projects.

### Releasing to Maven Central

1. mvn clean deploy
2. mvn release:clean release:prepare
   In case of failure:
   1. mvn release:rollback
   2. mvn release:clean
3. mvn release:perform
4. inspect the Sonatype staging repo and manually release, or
   1. set nexus-staging-maven-plugin's autoReleaseAfterClose=true for 
   the automated releases 


### For more see the [JavaDoc Documentation](https://protobufel.github.io/protobufel-maven-parent/javadoc/ "JavaDoc and more").  

Happy coding,

David Tesler
