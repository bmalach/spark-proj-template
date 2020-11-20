# spark-proj-template
Sample Apache Spark Java project

Build project:
```
mvn package
```

Run project with Spark:
```
spark-submit --class "sparkdemo.SparkDemo" --master local ./sparkexample-0.0.1-SNAPSHOT.jar
```

Run project with Java only (or run the main method in your IDE):
```
java -jar target/sparkexample-0.0.1-SNAPSHOT.jar
```
