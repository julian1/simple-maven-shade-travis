
Maven shade example to package the artifact in an uber-jar,

See pom.xml

#### build
```
mvn clean install
```

#### test
```
mvn test
```

#### run jar
```
java -jar target/simple-1.0-SNAPSHOT.jar
```

#### run class file with lib dependencies on the class loader path
```
java -cp 'target/classes:target/lib/*' com.hmkcode.Math
```

