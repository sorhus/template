Maven template for `java` / `scala` / `clojure`

```bash
mvn clean package
for class in JMain SMain CMain
do 
  java -cp target/template-0.0.1-SNAPSHOT-jar-with-dependencies.jar com.github.sorhus.template.$class
done
```
```
Hello Java World!
Hello Scala World!
Hello Clojure World!
```
