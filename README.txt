# Execute
```sh
./gradlew bootJar
java -jar build/libs/k8s-1.0.0.jar
```

# Access
```sh
curl http://localhost:8090/city/1
curl http://localhost:8090/city/2
...
curl http://localhost:8090/city/4079
```
