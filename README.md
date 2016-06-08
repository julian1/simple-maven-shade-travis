
## Simple maven shade example
# rather than mvn assembly ? 

Maven Shade example to create a single jar
See pom.xml


#### build
```
mvn clean install
```


#### Run jar
```
java -jar target/simple-1.0-SNAPSHOT.jar
```


#### Run class file with lib dependencies on the class loader path
```
java -cp 'target/classes:target/lib/*' com.hmkcode.Math
```


### build executable with exploded deps - deprecated
```
mvn clean compile assembly:single
java -cp ./target/simple-1.0-SNAPSHOT-jar-with-dependencies.jar com.hmkcode.S3Sample
```


