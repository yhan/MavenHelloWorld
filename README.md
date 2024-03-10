Maven top level structure conventions: 
--
1. src

src/main/java  
    java code
    pkg declaration
    other languages

src/test
    testing (under /test)
target  
pom.xml  

2. target
   Compilation directory
   Tests
   pkg contents

Maven commands
-
mvn clean  

mvn compile  

mvn package  (wrap everything to `packaging` type defined in pom file)  

mvn install  (to local directory)  

  to ~/.m2/repository  
  stores artifact to groupId/artifactId/version
  why: avoid duplication
 
mvn deploy  (to remote directory)  

