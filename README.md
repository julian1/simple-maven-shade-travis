

[![Build Status](https://travis-ci.org/aodn/aodn-portal.png?branch=master)](https://travis-ci.org/aodn/aodn-portal)

[Travis](https://travis-ci.org/julian1-io/simple-maven-shade-travis)

## Simple maven shade example

Maven Shade example to create a single jar

See pom.xml

#### build
```
mvn clean install
```

#### test
```
mvn test
```

#### Run jar
```
java -jar target/simple-1.0-SNAPSHOT.jar
```

#### Run class file with lib dependencies on the class loader path
```
java -cp 'target/classes:target/lib/*' com.hmkcode.Math
```

